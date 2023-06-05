From maven
COPY  pom.xml /user/local/service/pom.xml
COPY  src /user/local/service/src
WORKDIR /user/local/service
RUN mvn package

CMD [ "java", "-cp", "target/HolaMundoMaven-1-0-SNAPSHOT.jar", "com.example.demo.DemoApplication" ]

