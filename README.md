# shoping-chart
shopping-cart-pusher
This web application shows you how to program a simple shopping cart in React with a Java backend, using Pusher to add realtime features. Follow the tutorial here.

The stack:

Java 8
Maven as the build manager
Spring Boot with Spring MVC as the server-side framework
React in the front-end
Getting Started
Clone this repository and cd into it.

Replace the credentials in com.pusher.constants.PusherConstants.java with your own constants.

In index.html set the constants in lines 39,40,41 to be your own.

Start the application with one of the following commands (if you're using an IDE like Eclipse, just run the class com.pusher.ShoppingCartApplication):

mvn spring-boot:run
Or

mvn package -DskipTests
java -jar target/shopping-cart-0.0.1-SNAPSHOT.jar 
Go to http://localhost:8080 and start playing with the app

Prerequisites
A Pusher account
Java 8
Maven
Built With
Pusher - APIs to enable devs building realtime features
Maven - Dependency Management
Spring Boot - To create the Spring application
Acknowledgments
Thanks to Pusher for sponsoring this tutorial.
License
MIT
