FROM openjdk:20
COPY target/my_first_app-1.0-SNAPSHOT-jar-with-dependencies.jar myapplication.jar
COPY src/main/resources/Images/brain-mech.jpg mebr.jpg
ENTRYPOINT ["java","-jar","/myapplication.jar"]