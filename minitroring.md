**Cloud watch**


***Cloud watch*** - is a service that allows you to monitor various elements of your AWS account, collect and tract metrics:

- monitor metricsof AWS resources - eg EC2 instances
- cvreate custom metrics
- monitor and store logs
- set alarms and events

***

**Cloud Trial** (for AUDIT)- allows monitor all action taken by IAM users.

AWS CloudTrail is a web service that records activity made on your account and delivers log files to an Amazon S3 bucket CloudTrail is for auditing (CloudWatch is for performance monitoring)

**Alarm States:**

An alarm has the following possible states:

• OK—The metric or expression is within the defined threshold.

• ALARM—The metric or expression is outside of the defined threshold.

• INSUFFICIENT_DATA—The alarm has just started, the metric is not available, or not enough data is available for the metric to determine the alar m
state.


***
**SNS**

Simple Notification Service - automate the sending of email or text message notification based on events.

• Amazon Simple Notification Service (Amazon SNS) is a web service that makes it easy to set up, operate, and send notifications from the 
• Amazon SNS is used for building and integrating loosely-coupled, distributed applications

SNS:

- TOPICS - how you label and group different endpoints
- SUBSCRIPTIONS - endpoints (email address, phone numbers of your system admin)
- PUBLISHERS - human that gives SNS the message that needs to be sent
CW alarms triggers a text message