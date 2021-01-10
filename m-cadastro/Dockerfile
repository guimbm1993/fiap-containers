FROM maven:3.6.3-jdk-11-slim
COPY . /usr/src/myapp
WORKDIR /usr/src/myapp
RUN mvn clean package -Dmaven.test.skip=true
CMD java -jar ./target/m-cadastro-0.0.1-SNAPSHOT.jar
EXPOSE 8080