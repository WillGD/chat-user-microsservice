# Read Me First
The following was discovered as part of building this project:

* The original package name 'chatapp.chat-user-microsservice' is invalid and this project uses 'chatapp.chat_user_microsservice' instead.

# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/3.4.4/maven-plugin)
* [Create an OCI image](https://docs.spring.io/spring-boot/3.4.4/maven-plugin/build-image.html)
* [Spring Web](https://docs.spring.io/spring-boot/3.4.4/reference/web/servlet.html)
* [Docker Compose Support](https://docs.spring.io/spring-boot/3.4.4/reference/features/dev-services.html#features.dev-services.docker-compose)
* [Spring Data JPA](https://docs.spring.io/spring-boot/3.4.4/reference/data/sql.html#data.sql.jpa-and-spring-data)
* [WebSocket](https://docs.spring.io/spring-boot/3.4.4/reference/messaging/websockets.html)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/3.4.4/reference/using/devtools.html)
* [Spring Cloud Gateway Access Control [Enterprise]](https://techdocs.broadcom.com/us/en/vmware-tanzu/spring/spring-cloud-gateway-extensions/1-0-0/scg-extensions/access-control.html)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/rest/)
* [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)
* [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/)
* [Using WebSocket to build an interactive web application](https://spring.io/guides/gs/messaging-stomp-websocket/)

### Docker Compose support
This project contains a Docker Compose file named `compose.yaml`.
In this file, the following services have been defined:

* mysql: [`mysql:latest`](https://hub.docker.com/_/mysql)
* postgres: [`postgres:latest`](https://hub.docker.com/_/postgres)

Please review the tags of the used images and set them to the same as you're running in production.

## VMware Tanzu Spring Enterprise Extensions

You have selected to add [Tanzu Spring](https://www.vmware.com/products/app-platform/tanzu-spring) enterprise extensions to your project.
In order to use these enterprise extensions you must have authorized [access to the Spring Enterprise Subscription](https://techdocs.broadcom.com/us/en/vmware-tanzu/spring/tanzu-spring/commercial/spring-tanzu/guide-artifact-repository-administrators.html) artifacts with an entitlement to Tanzu Spring.
To learn more about what is included with Tanzu Spring entitlement, check out [enterprise.spring.io](https://enterprise.spring.io/) for more information.

### Maven Parent overrides

Due to Maven's design, elements are inherited from the parent POM to the project POM.
While most of the inheritance is fine, it also inherits unwanted elements like `<license>` and `<developers>` from the parent.
To prevent this, the project POM contains empty overrides for these elements.
If you manually switch to a different parent and actually want the inheritance, you need to remove those overrides.

