FROM tomcat
MAINTAINER Sebastian Goerke <sgoerke@csc.com>

# set deegree version
ENV DEEGREE_VERSION 3.3.14

# download deegree
RUN wget http://repo.deegree.org/content/repositories/public/org/deegree/deegree-webservices/${DEEGREE_VERSION}/deegree-webservices-${DEEGREE_VERSION}.war -O /usr/local/tomcat/webapps/deegree-webservices.war

CMD ["catalina.sh", "run"]
