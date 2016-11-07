FROM tolja/alpine-java
ADD build/libs/eureka-server.jar .
CMD /usr/bin/java -Xmx400m -Xms400m -jar eureka-server.jar
EXPOSE 8761