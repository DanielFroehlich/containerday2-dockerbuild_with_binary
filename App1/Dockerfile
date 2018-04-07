FROM containerday-baseimg/siemens-jdk18:latest
COPY sampleJavaApp.jar /home/jboss/
CMD echo "Daniel was here" >/home/jboss/message.txt
EXPOSE 8080
ENTRYPOINT  java -jar /home/jboss/sampleJavaApp.jar 
