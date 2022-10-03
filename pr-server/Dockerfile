# FROM nginx:1.23.1
FROM nginxinc/nginx-unprivileged:1.22

COPY /conf.d/* /etc/nginx/conf.d
COPY /html/* /usr/share/nginx/html

# RUN mkdir /usr/share/nginx/html/public
# RUN mkdir /var/cache/nginx/client_temp

# RUN useradd -u 8877 normal_user
# RUN chown -R normal_user /var/cache/nginx/client_temp
# USER normal_user 

