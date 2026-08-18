# Introduction to JAVA
- Java is a high-level, object-oriented programming language
- It is robust and secure language
- Java program should be saved with extension as .java
---
### Platform :
- Any hardware or software environment in which a program runs is known as a platform
- Java has a runtime environment (JRE) and its API (Application Programming Interface)

#### Java SE :
- Java Standard Edition is a programming platform 
- It has API's like java.lang , java.net , java.util , java.sql etc.

#### Java EE :
- Java Enterprise Edition is mainly used to develop web and enterprise applications
- It is built on top of the Java SE platform
- It includes Servlet , Web Services .etc.

#### JavaFX :
- JavaFX is used to develop rich internet applications
- It uses a lightweight user interface API

---
### Features Of Java :

#### - Simple :
Java is very easy  to learn 
#### - Object Oriented :
Everything in java is an object 
#### - Portable :
It facilitates you to carry the java bytecode to any platform 
#### Platform Independent :
Write Once and Run anywhere language
#### Secured :
There is no explicit pointer and programs run inside a VM sandbox
#### Robust :
It uses strong memory management and automatic garbage collection 
#### Multi-threaded :
Programs can be defined by multiple threads having common memory area

---
### Syntax of a Basic Java program :

``` java
public class <class-name>{
  // <Class-name> is the name of the class and also the name of the file
  // Other Methods can be written here

  public static void main(String[] args){
      // This is the main function , where the Program exec begins
      //Block of code

  }
}
```

The above syntax shows how a basic java program is structured  
- public : This makes the method / class visible [explained in later sections]
- class : This is a keyword for defining a class
- static : This lets the method run without creating an object
- void : This defines the return type of the method
- String[] args : This accepts the external text arguments from the user
  

---
### Identifiers :
- An Identifier is a unique name given to programming elements such as variables , classes , methods etc ..
- This is a predefined name which can not be used for other purposes

#### Rules for naming java identifiers :
- It should start with alphabet and can have numericals in between
- It can contain "_" but not any other special characters
   
