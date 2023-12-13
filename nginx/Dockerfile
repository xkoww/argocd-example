FROM rockylinux:9.3.20231119-minimal
RUN yum install -y epel-release && \
    yum install -y nginx

COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf

CMD /usr/sbin/nginx -g 'daemon off;'
