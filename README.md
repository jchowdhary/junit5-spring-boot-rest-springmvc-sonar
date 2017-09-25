This code will show how an Spring Rest Based Application using Spring Boot have used JUnit5 for creating Test cases.
IN this example we are using Spring Boot version 2 and Spring 5.

This project will also work with sonar and it will show code coverage.For this few things have been added in the POM file
 - Add the jacoco-maven-plugin and configure it to have the Test and Integretion Test.
 - Configure the Maven Surefire plugin to run the unit test coverage.
 - Configure the Maven failsafe plugin to run the integreation test coverage.
 - Add the sonar profile and set the sonar properties(make sure your sonar is already running, here it is running in localhost:9000
 - Check the sonar properties for username/password for db connection and also set the appropiate db driver and db connection url.(You    
   will find it from <sonar_dest_dir>/conf/sonar.properties, some properties need to uncommented to work.)
   
 To put the project in Sonar, execute
  - mvn sonar:sonar
  Once the maven command is executed sucessfully, you will see the project in the sonar in http://localhost:9000


