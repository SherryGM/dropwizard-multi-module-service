#  Sample application to Demo multi module Dropwizard project with Zipkin , Feign Client and immutables.github.io library integration
 
 

How to start the srv1 application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/dropwizard-srv1-1.0-SNAPSHOT.jar server config.yml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`
