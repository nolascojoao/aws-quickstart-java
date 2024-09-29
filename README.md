# App

This project provides a quickstart guide for using the [AWS Java SDK 2.x](https://github.com/aws/aws-sdk-java-v2) to programmatically connect to Amazon S3 and upload files.

---

## Getting Started

To replicate this project from scratch, follow the [AWS SDK for Java 2.0 Getting Started Guide](https://docs.aws.amazon.com/sdk-for-java/latest/developer-guide/get-started.html) 

---

## Prerequisites
- Java 1.8+
- Apache Maven

---

## Project Structure 

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

---

#### Building and Running the Project
1. To build the project:
```
mvn clean package
```
2. To run:
```
mvn exec:java -Dexec.mainClass="org.example.App"
```
