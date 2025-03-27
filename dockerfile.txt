FROM tomcat:latest
COPY ./webapp.war  /usr/local/tomcat/webapps/
CMD ["catalina.sh", "run"]
