FROM ubi7/ubi:7.7
MAINTAINER ANDRE <ANDRE.ALMEIDA@IFRN.EDU.BR>
LABEL description="Container Apache usando UBi 7"
RUN yum install -y httpd && yum clean all
RUN echo "MEU PRIMEIRO DOCKERFILE" > /usr/share/httpd/noindex/index.html
EXPOSE 80
ENTRYPOINT ["httpd","-D","FOREGROUND"]

