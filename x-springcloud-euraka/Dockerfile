FROM anapsix/alpine-java:8_server-jre_unlimited

RUN mkdir -p /home/workspace2

WORKDIR /home/workspace2

EXPOSE 2102

ADD ./target/x-springcloud-euraka-1.0.0-SNAPSHOT.jar ./app.jar

ENTRYPOINT ["java", "-jar", "app.jar"]

CMD ["--spring.profiles.active=dev"]
