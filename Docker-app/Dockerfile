FROM tomcat:8-jre11

RUN rm -rf /usr/local/tomcat/webapps/*

COPY /target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war
RUN useradd tomcat && chown -R tomcat:tomcat /usr/local/tomcat/
USER tomcat
CMD ["catalina.sh", "run"]

#this is a comment 1
