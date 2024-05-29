FROM openjdk:21
ARG JAR_FILE=stock.jar
COPY ${JAR_FILE} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]
EXPOSE 8081