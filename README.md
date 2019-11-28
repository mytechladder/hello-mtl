# Hello-MTL

This example shows how to create a microservices architecture with Spring Boot. It also shows how to package each application in Docker containers and deploy them with Github actions.

Please read [Build Spring Microservices and Dockerize them for Production](https://developer.okta.com/blog/2019/02/28/spring-microservices-docker) for a tutorial that shows you how to build this application.

**Prerequisites:** [Java 8 or 11](https://adoptopenjdk.net/).

* [Getting Started](#getting-started)
* [Help](#help)
* [Links](#links)
* [License](#license)

## Getting Started

To install this example application, run the following commands:

```bash
git clone 
cd okta-spring-microservices-docker-example
```

Run the following command from the root folder to create Docker containers for all your apps.

```shell
./mvnw clean install
```

Then you can start your microservices architecture using Docker Compose:

```shell
docker-compose up -d
```

**TIP:** You can use [Kitematic](https://kitematic.com/) to view your container logs and make sure everything starts OK.

After everything starts, you should be able to log in with your credentials at `http://localhost:8080`.

## Links

This example uses the following open source projects:

* [Spring Boot](https://spring.io/projects/spring-boot)
* [Spring Cloud](https://spring.io/projects/spring-cloud)
* [Spring Security](https://spring.io/projects/spring-security) 

## License

Apache 2.0, see [LICENSE](LICENSE).
