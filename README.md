# Spring Boot - HelloWorld Sample

This is a sample application of Spring Boot written at a hands-on workshop of Japan Grails/Groovy User Group meetup at 2014-08-01.
See <http://www.slideshare.net/makingx/grails-30-spring-boot> (written in Japanese).


## How to run

You can build and run this sample using Maven:

```
$ mvn spring-boot:run
```

Then access the app via a browser (or curl) on http://localhost:8080.


## How to build a JAR file

If you want to run the application outside of Maven, then first build the JARs and then use the `java` command:

```
$ mvn package
$ java -jar target/jggug-helloworld-1.0.0-SNAPSHOT.jar
```
