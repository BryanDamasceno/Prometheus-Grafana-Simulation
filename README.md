# prometheus-grafana-simulation

This project was developed to test Prometheus and Grafana tools. It is an API developed to generate custom metrics using Spring Boot Actuator. The Client container is a shell script that makes random requests on the application's routes to generate data.

To run the application:

build the app dir with maven:

```
- mvn clean package
```
and then:

```
- docker-compose up -d
```
Prometheus GUI is on the endpoint:

```
- localhost:9090
```
