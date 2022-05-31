# Getting Started
[OPIS NAS STONIE WWW](https://www.baeldung.com/spring-boot-postgresql-docker)
PROJEKT POZWALA PO URUCHOMIENIU DOCKER-COMPOSE UP W FOLDERZE  DOCKER URUCHOMIĆ CONTENERY
POSTGRESA I APLIKACJI SPRING. APLIKACJA SPRING MUSI BYC MANUALNIE KOPIOWANA  W POSTACI PLIKU JAR
DO FOLDERU DOCKER.
```
./mvnw clean package -DskipTests
cp target/docker-spring-boot-postgres-0.0.1-SNAPSHOT.jar src/main/docker
```
W naszym przypadku "docker-spring-postgres" należy zmienić na demo
```
./mvnw clean package -DskipTests
cp target/demo-0.0.1-SNAPSHOT.jar src/main/docker
```
W celu przebudowy projektu
```
cd src/main/docker
docker-compose down
docker rmi demo:latest
docker-compose up
```
### Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Boot Maven Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/2.7.0/maven-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/2.7.0/maven-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/2.7.0/reference/htmlsingle/#web)
* [Spring Boot DevTools](https://docs.spring.io/spring-boot/docs/2.7.0/reference/htmlsingle/#using.devtools)
* [Spring Configuration Processor](https://docs.spring.io/spring-boot/docs/2.7.0/reference/htmlsingle/#appendix.configuration-metadata.annotation-processor)

### Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)



|     |     |     |
|-----|-----|-----|
|     |     |     |
|     |     |     |

#### PRZYKŁADOWY MARKDOWN
<table>
<tr>
<th>Json 1</th>
<th>Markdown</th>
</tr>
<tr>
<td>
<pre>
{
  "id": 1,
  "username": "joe",
  "email": "joe@example.com",
  "order_id": "3544fc0"
}
</pre>
</td>
<td>

```json
{
  "id": 5,
  "username": "mary",
  "email": "mary@example.com",
  "order_id": "f7177da"
}
```

</td>
</tr>
</table>