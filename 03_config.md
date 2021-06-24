### III.	Config

Everything that varies between different deploys across environments (staging, production, developer environments, etc.) is categorized as configuration. This includes - 
- Database, Distributed Cache, and other backing services configuration
- Credentials to external services such as Azure Event Hub, Amazon S3, or Media Server
- Application connectivity information like IP Addresses, ports, and hostnames, etc.

Application Configuration should never be hardcoded. The principle suggests saving the configuration values in the environment variables or externalize the configuration from the application. In the Java world, one of the examples of externalizing the application configuration is the use of Spring-Cloud-Config.

For instance, the Spring Framework provides a configuration file where such configurations can be declared and attached to environment variables:

```sh
spring.datasource.url=jdbc:mysql://${MYSQL_HOST}:${MYSQL_PORT}/movies
spring.datasource.username=${MYSQL_USER}
spring.datasource.password=${MYSQL_PASSWORD}
```
