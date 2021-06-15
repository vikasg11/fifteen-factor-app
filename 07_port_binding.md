### VII.	Port binding

Export services via port binding – The twelve-factor app is completely self-contained and does not rely on the runtime injection of a webserver into the execution environment to create a web-facing service. From a Java perspective, Spring boot is one of the examples as it by default comes with an embedded server.

For instance, for a docker container, it allows to bind and expose the application on specific port only -
```sh
docker run --restart always --name mysql8.0 --net dev-network -v /tools/ext-docker/mysqlext:/var/lib/mysql -p 3306:3306 -d -e MYSQL_ROOT_PASSWORD=some-pass mysql:8.0
```
