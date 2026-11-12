# Spring Boot Demo walkthrough

## Business problem

A developer exploring the upstream Spring Boot examples needs a small module that traces an HTTP request from routing to response.

## Reproduce the workflow

With the Java 8 and Maven toolchain required by the module, run `mvn -pl demo-helloworld -am package`, then `java -jar demo-helloworld/target/demo-helloworld.jar`. Call `curl --fail http://127.0.0.1:8080/hello`.

Source inspection confirmed the Maven module and the `GET /hello` route.

## Verification

Source and documentation review.

## Limitations

The walkthrough covers the inherited demo-helloworld module. Upstream source and attribution are retained. The walkthrough was checked against the source and POM. A Maven build and runtime request were outside this verification.
