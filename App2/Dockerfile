FROM containerday-baseimg/siemens-jdk18:latest
COPY sampleJavaApp.jar /home/jboss/
RUN echo "Daniel was here the second time" >/home/jboss/message.txt
EXPOSE 8080
ENTRYPOINT  java -jar /home/jboss/sampleJavaApp.jar
