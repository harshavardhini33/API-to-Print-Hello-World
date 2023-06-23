# EXP 23 - CREATE API TO PRINT HELLO WORLD

## AIM:
To create an API to print Hello World

## ALGORITHM:

1) Create a spring boot project using Spring Initilzr.
2) Add required dependencies.
3) Choose the configuration file type i.e, either Gradle or Maven.
4) Add a method called hello in the Application.java program
5) Run the project.
6) View the result at http://localhost:8080/

## PROGRAM:

### Controller.java
```
java

package com.project.javafullstack.controller;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RestController;
@RestController
public class Controller {
 @GetMapping("/hello")
 public String hello(){
 return "Hello World";
 }
}
```


## OUTPUT:

<img width="454" alt="image" src="https://github.com/Monisha-11/API-TO-PRINT-HELLO-WORLD/assets/93427240/6b178230-b556-4827-a8fb-2edc967d8d8e">

## RESULT:
Hence, an API to print Hello World is created and executed successfully
