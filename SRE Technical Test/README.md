This is a sample application.

This application exposes a simple REST API on port 8080, with a single GET endpoint:

/greeting

This endpoint returns a JSON response of the following format:

```{"id":1,"content":"Hello, World!"}```

Build Requirements:

* Java 1.8
* Maven

Runtime Requirements: 

* Java 1.8

To run unit tests, execute from the root of this folder:

```mvn test```

To build the package, run

```mvn package```

To remove a previous build result, run

```mvn clean```

The executable binary will be in the *target* subfolder. To execute, run

```java -jar target/srt-rest-service-0.1.0.jar```

The web service can then be accessed via http://localhost:8080/greeting