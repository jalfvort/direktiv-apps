---
{
  "image": "jkizo/amazon-sns",
  "desc": "Writes a message to Amazon's Simple Notification Service"
}
---

# Amazon SNS

Writes a message to Amazon's Simple Notification Service

## Direktiv

An example workflow of writing 'Hello World!' to the notification service.

```yaml
id: write-helloworld
functions:
- id: write
  image: vorteil/amazon-sns
description: "Writes 'Hello World!' to an Amazon Simple Notification Service"
states:
- id: write-message
  type: action
  action:
    function: write
    input: .
```

## Input

The input required to run the above workflow properly is the following:

```json
{
    "key": .secrets.AMAZON_KEY,
    "secret": .secrets.AMAZON_SECRET,
    "region": "ap-southeast-2",
    "topic-arn": .secrets.TOPIC_ARN,
    "message": "Hello World!"
}
```

## Output

If the action is successful, no output will be returned.

## Error

In the case that an error is encountered, it will present in the following format:

```json
{
    "errorCode": "com.amazon-sns.error",
    "errorMsg": "Something went wrong"
}
```