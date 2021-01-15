# Spring Boot Demo App
 
 This is a maven based project. 
 
 - Using the below command on CLI to build and run project for development purposes.
 ```
 mvn spring-boot:run
 ```

- To create the jar of the project separately and then run, use any of the following commands.

```
mvn clean package 

or

mvn clean install
```

```
java -jar <name of jar file> // Run the project using the created jar file
```

Note: Difference between the below 2 commands:

```
mvn clean install // Compiles, package and put the package in the local .m2 repository   

mvn clean package // Compiles the code and package it. 
```
