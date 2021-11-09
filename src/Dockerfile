FROM java:8
RUN mkdir -p /home/javaserver/
WORKDIR /home/javaserver/
COPY . /home/javaserver/
#CMD ["java -classpath 'javaServer.jar' Server"]
ENTRYPOINT ["java","-classpath","javaServerUpdate.jar","Server"]




#FROM java:8
#VOLUME /tmp
#COPY ../src/out/target/resource-1.jar resource.jar
#RUN bash -c "touch /resource.jar"
#EXPOSE 80
#ENTRYPOINT ["java","-jar","resource.jar"]

#docker run -d -p 18080:8080 --name docker-resource leesia/resource:1.0



#FROM java:8
#EXPOSE 80
#ADD /out/artifacts/JavaGitHub_jar.jar /server/JavaGitHub_jar.jar
#ENTRYPOINT ["java","-jar","JavaGitHub_jar.jar"]
#end