FROM java:8-alpine

#COPY target/spring-boot-basewebapp-0.0.1-SNAPSHOT.jar /data
ADD target/spring-boot-basewebapp-0.0.1-SNAPSHOT.jar app.jar
ENV JAVA_OPTS=""
ENTRYPOINT [ "sh", "-c", "java $JAVA_OPTS  -jar /app.jar" ]