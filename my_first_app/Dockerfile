FROM openjdk:20
MAINTAINER ManojkumarAnanthu
COPY target/my_first_app-1.0-SNAPSHOT-jar-with-dependencies.jar app.jar
COPY src/main/resources/Images/nagralogo-1.png manoj.png
ENTRYPOINT ["java","-jar","/app.jar"]