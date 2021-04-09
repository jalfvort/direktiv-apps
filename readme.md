# Direktiv Apps

Simple Containers that run on Direktiv

<em>created by [38b4b190](https://github.com/vorteil/direktiv-apps/tree/38b4b190c2c5242b4f20dc1e66c57ae0d0d89e8d)</em>


## Containers

| Image | Description | How to Use |
| ----- | ----------- | ---------- |
| [jkizo/amazon-sns](https://hub.docker.com/r/vorteil/amazon-sns) | Writes a message to Amazon's Simple Notification Service | [README](https://github.com/vorteil/direktiv-apps/tree/master/amazon-sns) |
| [jkizo/amazon-upload](https://hub.docker.com/r/vorteil/amazon-upload) | Uploads a base64 encoded string to a blob on Amazon. | [README](https://github.com/vorteil/direktiv-apps/tree/master/amazon-upload) |
| [jkizo/aws-ec2-create](https://hub.docker.com/r/vorteil/aws-ec2-create) | Creates an amazon ec2 instance on aws. | [README](https://github.com/vorteil/direktiv-apps/tree/master/aws-ec2-create) |
| [jkizo/aws-ec2-delete](https://hub.docker.com/r/vorteil/aws-ec2-delete) | Delete a amazon ec2 instance. | [README](https://github.com/vorteil/direktiv-apps/tree/master/aws-ec2-delete) |
| [jkizo/aws-ec2-start](https://hub.docker.com/r/vorteil/aws-ec2-start) | Start a amazon ec2 instance. | [README](https://github.com/vorteil/direktiv-apps/tree/master/aws-ec2-start) |
| [jkizo/aws-ec2-stop](https://hub.docker.com/r/vorteil/aws-ec2-stop) | Stops a amazon ec2 instance. | [README](https://github.com/vorteil/direktiv-apps/tree/master/aws-ec2-stop) |
| [jkizo/awsgo](https://hub.docker.com/r/vorteil/awsgo) | Executes any cli command with aws using a golang wrapper to provide the authentication before executing. | [README](https://github.com/vorteil/direktiv-apps/tree/master/awsgo) |
| [jkizo/awslog](https://hub.docker.com/r/vorteil/awslog) | Writes a log line to aws cloudwatch logs with provided log stream and group. | [README](https://github.com/vorteil/direktiv-apps/tree/master/awslog) |
| [jkizo/azgo](https://hub.docker.com/r/vorteil/azgo) | Executes any azure cli command using a golang wrapper to provide the authentication before executing. | [README](https://github.com/vorteil/direktiv-apps/tree/master/azgo) |
| [jkizo/azinvoke](https://hub.docker.com/r/vorteil/azinvoke) | Executes a cloud function on azure using the function name, function app and function key as authentication to do so. | [README](https://github.com/vorteil/direktiv-apps/tree/master/azinvoke) |
| [jkizo/azlog](https://hub.docker.com/r/vorteil/azlog) | Writes a log line to Azure Log Analytics Workspace. | [README](https://github.com/vorteil/direktiv-apps/tree/master/azlog) |
| [jkizo/azure-servicebus](https://hub.docker.com/r/vorteil/azure-servicebus) | Writes a message to Azure's Servicebus | [README](https://github.com/vorteil/direktiv-apps/tree/master/azure-servicebus) |
| [jkizo/azure-upload](https://hub.docker.com/r/vorteil/azure-upload) | Uploads a base64 encoded string to a blob on Azure. | [README](https://github.com/vorteil/direktiv-apps/tree/master/azure-upload) |
| [jkizo/debug](https://hub.docker.com/r/vorteil/debug) | Prints all the information that direktiv sends to the container | [README](https://github.com/vorteil/direktiv-apps/tree/master/debug) |
| [jkizo/discordmsg](https://hub.docker.com/r/vorteil/discordmsg) | Writes a discord message to a webhook URL. | [README](https://github.com/vorteil/direktiv-apps/tree/master/discordmsg) |
| [jkizo/elasticsearch](https://hub.docker.com/r/vorteil/elasticsearch) | Writes a new JSON document to an index or queries an index in its entirety. | [README](https://github.com/vorteil/direktiv-apps/tree/master/elasticsearch) |
| [jkizo/gcloud](https://hub.docker.com/r/vorteil/gcloud) | Executes a gcloud cli command using a golang wrapper to provide authentication via service account key file. | [README](https://github.com/vorteil/direktiv-apps/tree/master/gcloud) |
| [jkizo/gcloud-instance-create](https://hub.docker.com/r/vorteil/gcloud-instance-create) | Create a compute engine instance on google cloud. | [README](https://github.com/vorteil/direktiv-apps/tree/master/gcloud-instance-create) |
| [jkizo/gcloud-instance-delete](https://hub.docker.com/r/vorteil/gcloud-instance-delete) | Delete a compute engine instance on google cloud. | [README](https://github.com/vorteil/direktiv-apps/tree/master/gcloud-instance-delete) |
| [jkizo/gcloud-instance-start](https://hub.docker.com/r/vorteil/gcloud-instance-start) | Starts a compute engine instance on google cloud. | [README](https://github.com/vorteil/direktiv-apps/tree/master/gcloud-instance-start) |
| [jkizo/gcloud-instance-stop](https://hub.docker.com/r/vorteil/gcloud-instance-stop) | Stop a compute engine instance on google cloud. | [README](https://github.com/vorteil/direktiv-apps/tree/master/gcloud-instance-stop) |
| [jkizo/gcplog](https://hub.docker.com/r/vorteil/gcplog) | Writes a log line to a stackdriver logging implementation | [README](https://github.com/vorteil/direktiv-apps/tree/master/gcplog) |
| [jkizo/google-pubsub](https://hub.docker.com/r/vorteil/google-pubsub) | Writes a message to Google's Pubsub service. | [README](https://github.com/vorteil/direktiv-apps/tree/master/google-pubsub) |
| [jkizo/google-sentiment-check](https://hub.docker.com/r/vorteil/google-sentiment-check) | Reads a string and tells you the sentiment of the written text. | [README](https://github.com/vorteil/direktiv-apps/tree/master/google-sentiment-check) |
| [jkizo/google-translator](https://hub.docker.com/r/vorteil/google-translator) | Reads a string and converts it to the targeted language. | [README](https://github.com/vorteil/direktiv-apps/tree/master/google-translator) |
| [jkizo/google-upload](https://hub.docker.com/r/vorteil/google-upload) | Uploads a base64 encoded string to a bucket on Google. | [README](https://github.com/vorteil/direktiv-apps/tree/master/google-upload) |
| [jkizo/googleinvoke](https://hub.docker.com/r/vorteil/googleinvoke) | Executes a cloud function on google using a client authenticated via a service account key. | [README](https://github.com/vorteil/direktiv-apps/tree/master/googleinvoke) |
| [jkizo/googlemsg](https://hub.docker.com/r/vorteil/googlemsg) | Writes a google message to a webhook URL. | [README](https://github.com/vorteil/direktiv-apps/tree/master/googlemsg) |
| [jkizo/greeting](https://hub.docker.com/r/vorteil/greeting) | Outputs a greeting | [README](https://github.com/vorteil/direktiv-apps/tree/master/greeting) |
| [jkizo/imagerecognition](https://hub.docker.com/r/vorteil/imagerecognition) | Checks an image to see if it is safe for work and responds with content is likely to be racy, adult or violence themed. | [README](https://github.com/vorteil/direktiv-apps/tree/master/imagerecognition) |
| [jkizo/influxdb](https://hub.docker.com/r/vorteil/influxdb) | A container that provides the opportunities to write or query data on an InfluxDB instance. | [README](https://github.com/vorteil/direktiv-apps/tree/master/influxdb) |
| [jkizo/kafka](https://hub.docker.com/r/vorteil/kafka) | Writes a message to a Kafka service | [README](https://github.com/vorteil/direktiv-apps/tree/master/kafka) |
| [jkizo/lambda](https://hub.docker.com/r/vorteil/lambda) | Executes a cloud function on aws using their golang SDK. | [README](https://github.com/vorteil/direktiv-apps/tree/master/lambda) |
| [jkizo/rabbitmq](https://hub.docker.com/r/vorteil/rabbitmq) | Writes a message to the RabbitMQ Service | [README](https://github.com/vorteil/direktiv-apps/tree/master/rabbitmq) |
| [jkizo/redis](https://hub.docker.com/r/vorteil/redis) | Sets and gets on a redis memory store. | [README](https://github.com/vorteil/direktiv-apps/tree/master/redis) |
| [jkizo/request](https://hub.docker.com/r/vorteil/request) | Perform a basic HTTP/S request. | [README](https://github.com/vorteil/direktiv-apps/tree/master/request) |
| [jkizo/simplepostgresclient](https://hub.docker.com/r/vorteil/simplepostgresclient) | Perform simple interactions on a PostgreSQL database.  | [README](https://github.com/vorteil/direktiv-apps/tree/master/simplepostgresclient) |
| [jkizo/slackmsg](https://hub.docker.com/r/vorteil/slackmsg) | Writes a message to a slack webhook url | [README](https://github.com/vorteil/direktiv-apps/tree/master/slackmsg) |
| [jkizo/smtp](https://hub.docker.com/r/vorteil/smtp) | A simple smtp client to send an email | [README](https://github.com/vorteil/direktiv-apps/tree/master/smtp) |
| [jkizo/solve](https://hub.docker.com/r/vorteil/solve) | Solves math expressions | [README](https://github.com/vorteil/direktiv-apps/tree/master/solve) |
| [jkizo/store](https://hub.docker.com/r/vorteil/store) | Add a row to a 'Google Sheets' spreadsheet. | [README](https://github.com/vorteil/direktiv-apps/tree/master/store) |
| [jkizo/tweet](https://hub.docker.com/r/vorteil/tweet) | Tweets a message to a twitter account. | [README](https://github.com/vorteil/direktiv-apps/tree/master/tweet) |
| [jkizo/twilio](https://hub.docker.com/r/vorteil/twilio) | Sends an email or SMS message using Twilio. | [README](https://github.com/vorteil/direktiv-apps/tree/master/twilio) |

