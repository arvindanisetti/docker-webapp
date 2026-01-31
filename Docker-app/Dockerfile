FROM tomcat:9-jdk17-openjdk-slim

RUN rm -rf /usr/local/tomcat/webapps/*

COPY target/myweb-8.7.1.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080

CMD ["catalina.sh", "run"]
