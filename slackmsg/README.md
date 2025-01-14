---
{
  "image": "jkizo/slackmsg",
  "desc": "Writes a message to a slack webhook url"
}
---
## SlackMessage

Writes a message to a slack webhook url

## Direktiv

An example workflow of using the container on Direktiv

```yaml
id: post-to-slack
function:
- id: post
  image: vorteil/slack
description: "Send a message to a slack channel"
states:
- id: postToSlack
  type: action
  action:
    function: post
    input: .
```

## Input

The input needed to run the above workflow properly is the following:

```json
{
  "message": "This message will be posted to slack chat",
  "url": "SLACK_CHAT_WEBHOOK_URL"
}
```

## Output

If the action is successful, the slack chat message should appear in the appropriate channel it was sent to.

## Error

In the case that an error is encountered, it will present in the following format:

```json
{
  "errorCode": "com.slack.error",
  "errorMsg": "Something went wrong"
}
```