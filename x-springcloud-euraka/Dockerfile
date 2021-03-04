FROM anapsix/alpine-java:8_server-jre_unlimited

RUN mkdir -p /home/workspace/x-eureka

WORKDIR /home/workspace/x-eureka

EXPOSE 2100

ADD ./target/x-springcloud-euraka-1.0.0-SNAPSHOT.jar ./app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]

