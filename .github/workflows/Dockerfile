FROM eclipse-temurin:17-jdk

WORKDIR /app

COPY . .

RUN javac src/main/java/HelloWorld.java

CMD ["java", "-cp", "src/main/java", "HelloWorld"]
