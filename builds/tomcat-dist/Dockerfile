FROM tomcat:alpine

COPY ./tomcat/conf/server.xml $CATALINA_HOME/conf/server.xml
COPY ./tomcat/conf/tomcat-users.xml $CATALINA_HOME/conf/tomcat-users.xml
COPY ./tomcat/conf/Catalina/localhost/context.xml $CATALINA_HOME/conf/Catalina/localhost/manager.xml
COPY ./tomcat/conf/Catalina/localhost/context.xml $CATALINA_HOME/conf/Catalina/localhost/host-manager.xml
COPY ./tomcat/certificados $CATALINA_HOME/certificados