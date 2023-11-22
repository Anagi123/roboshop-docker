FROM nginx 
# 1.using official image nginx & 2.removing de-fault html.3.copy reverse proxy config.4.copy code
RUN rm -f /usr/share/nginx/html/index.html
COPY roboshop.conf /etc/nginx/default.d/roboshop.conf
ADD static usr/share/nginx/html/

