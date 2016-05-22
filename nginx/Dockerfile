FROM nginx

COPY WelcomePage /usr/share/nginx/welcome


RUN ["rm", "/etc/nginx/conf.d/default.conf"]
COPY configuration/conf.d/udd.conf  /etc/nginx/conf.d/



#COPY configuration/sites-available/udd /etc/nginx/sites-available/udd



