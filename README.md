<h3>Spring Boot Project with Swagger Code Generation</h3>

<div>
This project is a Spring Boot application that incorporates Swagger Code 
Generation to streamline the creation of REST APIs and their documentation. 
The setup enables developers to generate client and server code from Swagger 
specification, ensuring consistency and reducing manual effort.
</div>

## Features

* Spring Boot Framework: Leverages the robust and scalable Spring Boot framework for application development.
* Swagger Code Generation: Automatically generates API client and server code from an OpenAPI specification.
* Embedded Tomcat Server: Facilitates rapid development and testing without requiring an external server.
* Maven Build Tool: Uses Maven for dependency management and build automation.
* REST APIs: Easily define and implement REST APIs.

## Supported Languages

<strong>
The language parameter in the plugin configuration specifies the language for code generation. The following languages are supported:

* spring: Generates server-side code for Spring Boot.
* java: Generates Java client code.
* python: Generates Python client code.
* javascript: Generates JavaScript client code.

To change the language, update the <language> field in the plugin configuration and run the following command:

<p>mvn clean install</p>

</strong>

## Prerequisites

* Java Development Kit (JDK): Version 8 or later.
* Apache Maven: Version 3.6 or later.
* Swagger/OpenAPI Specification File: YAML format.

<h1>Getting Started</h1>

<h3><b>Clone the Repository</b></h3>

* git clone [https://github.com/Rahul70908/spring-boot-swagger-codegen.git](https://github.com/Rahul70908/Swagger-Code-Generator.git)
* cd spring-boot-swagger-codegen
* Place your OpenAPI specification file (e.g., data.yaml) in the src/main/resources directory.
* Update the swagger-codegen-maven-plugin configuration in the pom.xml
  file to point to your specification.

<b>Build the Project</b>

* mvn clean install
