# Introduction

This is my repository for coding allowing in the Manning Live Project [Asynchronous Event Handling Using Microservices and Kafka](https://www.manning.com/liveproject/asynchronous-event-handling-using-microservices-and-kafka).

The project builds a few (asynchronous) microservices communicating with Apache Kafka. For the Apache Kafka environment, I am selecting the latest & greatest [Confluent Docker Image](https://github.com/confluentinc/cp-all-in-one/blob/7.5.0-post/cp-all-in-one-kraft/docker-compose.yml).

Furthermore, instead of using Go as suggested by the project, I prefer to be using Python, as I am more familiar with the language and have no need for Go knowledge at this time.

## Topic Creation
As the confluent CLI has not been installed on the containers I verified, I have simply created the topics needeed using the Web Interface (Confluent Control Center) - installing the confluent cli locally and invoking it on the installed container using 'docker exec -ti broker bin/confluent .... ' left it complaining that the REST server had not been started and I did not want to spent too much time on simply creating topics, so I "cheated" a bit.
