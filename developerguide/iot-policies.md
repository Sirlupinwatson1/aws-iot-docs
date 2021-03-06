# AWS IoT Core Policies<a name="iot-policies"></a>

AWS IoT Core policies are JSON documents\. They follow the same conventions as IAM policies\. AWS IoT Core supports named policies so many identities can reference the same policy document\. Named policies are versioned so they can be easily rolled back\.

AWS IoT Core policies allow you to control access to the AWS IoT Core data plane\. The AWS IoT Core data plane consists of operations that allow you to connect to the AWS IoT Core message broker, send and receive MQTT messages, and get or update a device's shadow\.

An AWS IoT Core policy is a JSON document that contains one or more policy statements\. Each statement contains:
+ `Effect`, which specifies whether the action is allowed or denied\.
+ `Action`, which specifies the action the policy is allowing or denying\.
+ `Resource`, which specifies the resource or resources on which the action is allowed or denied\.

**Topics**
+ [AWS IoT Core Policy Actions](iot-policy-actions.md)
+ [AWS IoT Core Action Resources](iot-action-resources.md)
+ [AWS IoT Core Policy Variables](iot-policy-variables.md)
+ [Example AWS IoT Policies](example-iot-policies.md)
+ [Authorization with Amazon Cognito Identities](cog-iot-policies.md)