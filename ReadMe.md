#Spring Boot Project With Kafka

A spring boot application with Kafka

### <U>Installation</U>

The application is built using gradle and all the dependencies will be added automatically

###Prerequisites

https://docs.confluent.io/platform/current/installation/installing_cp/zip-tar.html#prod-kafka-cli-install

https://docs.confluent.io/confluent-cli/current/install.html

####Build the application:
```
gradle build
```

For Running Application in local:
```
$ gradle bootrun

```

#### Use Terminal to test the application using the below API endpoint:

```
curl -X POST -F 'message=test' http://localhost:9000/kafka/publish
```

#### Refer below document for more details

https://www.confluent.io/blog/apache-kafka-spring-boot-application/