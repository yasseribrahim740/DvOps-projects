FROM tomcat:8-jre11
LABEL Project="Vprofile"
LABEL Author="Yasser"


RUN rm -rf /usr/local/tomcat/webapps/*
COPY target/vprofile-v2.war /usr/local/tomcat/webapps/ROOT.war

EXPOSE 8080
CMD [ "catalina.sd","run" ]
WORKDIR /usr/local/tomcat/ 
VOLUME [ "/usr/local/tomcat/webapps" ] 