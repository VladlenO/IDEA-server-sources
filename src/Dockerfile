FROM java:8
RUN mkdir -p /home/javaserver/
WORKDIR /home/javaserver/
COPY . /home/javaserver/
EXPOSE 80/tcp
EXPOSE 80/udp
#CMD ["java -classpath 'javaServer.jar' Server"]
ENTRYPOINT ["java","-classpath","javaServerUpdate.jar","Server"]