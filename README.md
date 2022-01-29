# MAVEN FIX

During the creation of the web application, an initial problem I had was that the pom.xml file was outdated, I did not know this at first, but repeatedly was getting JAVA_HOME and JAVADOC errors when running the app. I put in a lot of research and was able to figure out what the issue was and update it and doing so I was also able to help my classmates, as the teacher had outputted an announcement to try to help them, but it did not fix my problem. I have included a discussion post in the class, in the MAVEN_FIX folder in this repository.

# GameAuth

How to start the GameAuth application
---

1. Run `mvn clean install` to build your application
1. Start application with `java -jar target/gameauth-0.0.1-SNAPSHOT.jar server config.yml`
1. To check that your application is running enter url `http://localhost:8080`

Health Check
---

To see your applications health enter url `http://localhost:8081/healthcheck`
