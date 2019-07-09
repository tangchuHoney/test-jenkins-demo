FROM java:8-alpine
VOLUME /mydata/tmp
ADD test-jenkins-demo.jar app.jar
EXPOSE 9090
ENTRYPOINT ["java","-jar","/app.jar"]