# App

This project contains a maven application with [AWS Java SDK 2.x](https://github.com/aws/aws-sdk-java-v2) dependencies.

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

## Documentos de referências com tudo necessário aos estudos

    aws-sdk-java-dg-v2 - EM INGLÊS.pdf
    aws-sdk-java-dg-v2 - EM PORTUGUÊS.pdf

Verificar resultados no arquivo
    Evidencias.png
    

