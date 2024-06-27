# App

This project is a quickstart demonstration for using the [AWS Java SDK 2.x](https://github.com/aws/aws-sdk-java-v2) dependencies. It demonstrates how to programmatically connect to Amazon S3 and upload files

## Getting Started

To replicate this project from scratch, follow the [Get Started with the AWS SDK for Java 2.x](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/get-started.html) guide provided by AWS

## Prerequisites
- Java 1.8+
- Apache Maven
- GraalVM Native Image (optional)

## Development

Below is the structure of the generated project.

```
├── src
│   ├── main
│   │   ├── java
│   │   │   └── package
│   │   │       ├── App.java
│   │   │       ├── DependencyFactory.java
│   │   │       └── Handler.java
│   │   └── resources
│   │       └── simplelogger.properties
│   └── test
│       └── java
│           └── package
│               └── HandlerTest.java
```

- `App.java`: main entry of the application
- `DependencyFactory.java`: creates the SDK client
- `Handler.java`: you can invoke the api calls using the SDK client here.

#### Building the project
```
mvn clean package
```
#### Running the project
```
mvn exec:java -Dexec.mainClass="org.example.App"
```