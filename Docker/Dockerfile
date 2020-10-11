FROM tomcat:latest

MAINTAINER SANTHOSH

RUN apt-get update -y

ADD https://mahalogindeploy.s3-us-west-1.amazonaws.com/mahaLogin-1.0.war /usr/local/tomcat/webapps/

EXPOSE 8080

ENTRYPOINT ["catalina.sh", "run"]


