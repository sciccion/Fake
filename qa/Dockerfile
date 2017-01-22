# Version: 0.0.1
   FROM centos:centos6
   MAINTAINER James Turnbull "somemail@mail.com"
   RUN yum -y update; yum clean all
   RUN yum -y install epel-release; yum clean all
   RUN yum -y install nginx
   RUN echo "Hi, I am in your container" >/usr/share/nginx/html/index.html
   CMD ["service nginx restart"]
   EXPOSE 80
