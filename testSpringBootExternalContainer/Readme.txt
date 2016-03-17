Reference
http://stackoverflow.com/questions/27904594/spring-boot-war-deployed-to-tomcat

Objective
:Deploy springBoot into external container

Start Method
1. mvn install
2. Run as > Run on server

Test URL
1. curl localhost:8080
	HelloWorld!
2. curl http://localhost:8080/testSpringBootExternalContainer/help
	Hi Please use...
3. curl http://localhost:8080/testSpringBootExternalContainer/greeting
	{"id":2,"content":"Hello, World!"}