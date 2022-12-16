FROM openjdk:11
COPY . .
RUN ./mvnw clean package
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "/target/calculator-0.0.1-SNAPSHOT.jar"]