FROM centos:latest
MAINTAINER raja@gmail.com

RUN yum install -y httpd
RUN /bin/systemctl start httpd.service
EXPOSE 80

CMD  'tail -f /etc/httpd/logs/access_logs'
