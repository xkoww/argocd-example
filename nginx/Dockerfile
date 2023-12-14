FROM rockylinux:9
RUN dnf install -y epel-release && \
    dnf install -y nginx

COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx/nginx.conf

CMD /usr/sbin/nginx -g 'daemon off;'