FROM registry.gitlab.com/gbraad/centos:systemd
MAINTAINER Gerard Braad <me@gbraad.nl>

RUN yum -y install httpd; yum clean all; systemctl enable httpd.service

EXPOSE 80
VOLUME ["/var/www/html"]

CMD ["/usr/sbin/init"]

