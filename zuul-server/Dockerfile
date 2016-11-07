FROM tolja/alpine-java
ADD build/libs/zuul-server.jar .
CMD java -Xmx600m -Xms600m -jar zuul-server.jar
EXPOSE 8080