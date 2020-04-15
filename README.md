# AWS Signature V4 Connector Example Project

This project is dependent on the AWS Signature Version 4 Connector: (https://github.com/djuang1/awsv4auth-extension)

<img src="https://github.com/djuang1/djuang1.github.io/blob/master/img/aws-sig-v4/aws-sig-v4-example-flow.png?raw=true" width="500px">

Publish the AWS Signature Version 4 Connector to your Exchange and reference the module in the pom.xml

```
<dependency>
    <groupId>[Group ID]</groupId>
    <artifactId>awsv4auth-extension</artifactId>
    <version>1.0.1</version>
    <classifier>mule-plugin</classifier>
</dependency>
```