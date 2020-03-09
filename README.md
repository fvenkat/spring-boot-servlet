# spring-boot-servlet

Spring Boot has Embedded Application server i.e. Tomcat , Undertow , Jetty servers
No Need to setup external tomcat setup , add tomcat as JAR file.

Make POM.xml file as per your server Need , I attached pom.xml file for all 3 server jetty , tomcat , undertow.

How to Run Sample Servlet


1. Replace localhost with your IP Address in /src/main/resources/application.properties file.

2. Install Maven Package in linux server using yum.

  yum install -y maven

3. Run the Maven Goal.

  mvn clean spring-boot:run

3. Application URL :- http://localhost:8085/myServlet?name=Spring-boot-demo
