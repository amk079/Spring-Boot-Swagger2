# Spring-Boot-Swagger2

1. Overview
When creating a REST API, good documentation is instrumental.

Moreover, every change in the API should be simultaneously described in the reference documentation. Accomplishing this manually is a tedious exercise, so automation of the process was inevitable.

In this tutorial, we will look at Swagger 2 for a Spring REST web service. For this article, we will use the Springfox implementation of the Swagger 2 specification.

The creation of the REST service we will use in our examples is not within the scope of this article. If you already have a suitable project, use it. If not, the following links are a good place to start:

Build a REST API with Spring 4 and Java Config article
Building a RESTful Web Service

3. Adding the Maven Dependency
As mentioned above, we will use the Springfox implementation of the Swagger specification. The latest version can be found on Maven Central.

To add it to our Maven project, we need a dependency in the pom.xml file.

<dependency>
    <groupId>io.springfox</groupId>
    <artifactId>springfox-swagger2</artifactId>
    <version>2.9.2</version>
</dependency>

4. Integrating Swagger 2 into the Project
5. Swagger UI
6. Advanced Configuration
The Docket bean of your application can be configured to give you more control over the API documentation generation process.
7. Swagger UI with an OAuth-secured API
