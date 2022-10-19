FROM nginxinc/nginx-unprivileged:1.22

USER root

COPY /conf.d/* /etc/nginx/conf.d
COPY /html/* /usr/share/nginx/html

RUN mkdir /usr/share/nginx/html/help_page
COPY /html/help_page/* /usr/share/nginx/html/help_page

USER nginx

