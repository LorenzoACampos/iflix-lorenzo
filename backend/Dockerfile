FROM eclipse-temurin:21-jdk
WORKDIR /app
COPY . .
RUN ./mvnw -B -DskipTest package 
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "target/iflix-0.0.1-SNAPSHOT.jar"]