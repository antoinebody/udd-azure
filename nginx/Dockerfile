FROM nginx

COPY WelcomePage /usr/share/nginx/welcome


RUN ["rm", "/etc/nginx/conf.d/default.conf"]
COPY configuration/conf.d/udd.conf  /var/tmp/

COPY configuration/conf.d/proxy.conf  /etc/nginx/proxy_conf/

COPY configuration/certificates /etc/nginx/certificates