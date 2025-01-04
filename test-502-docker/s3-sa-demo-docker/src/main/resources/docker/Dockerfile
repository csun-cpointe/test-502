FROM openjdk:17
RUN ls -la
COPY target/* /tmp
WORKDIR /tmp
RUN chmod -R 777 .
RUN ls -la
CMD ["java","-jar","s3-sa-demo-pipeline-1.1.0-SNAPSHOT-jar-with-dependencies.jar"]