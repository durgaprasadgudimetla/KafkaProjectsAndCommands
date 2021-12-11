https://sonusingh-javatech.medium.com/spring-boot-with-apache-kafka-on-windows-os-e1eed95b9000





start kafka server:

.\bin\windows\kafka-server-start.bat .\config\server.properties

creating topic with one partition:
----------------------------------

kafka-topics.bat --create --zookeeper localhost:2181 --replication-factor 1 --partitions 1 --topic "users"

to execute the producer:

.\bin\windows\kafka-console-producer.bat --broker-list localhost:9092 --topic users



to start consumer execute below command:

kafka-console-consumer.bat --bootstrap-server localhost:9092 -topic users




react js  -redux

constant   props




--------------------------------
https://github.com/The-Tech-Tutor/spring-react-login
https://www.youtube.com/watch?v=HV-9EIU9JVY
https://console.cloud.google.com/projectselector2/apis/credentials?pli=1&supportedpurview=project

https://github.com/callicoder/spring-boot-react-oauth2-social-login-demo

