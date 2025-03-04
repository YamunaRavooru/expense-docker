FROM nginx:stable-alpine3.20-perl
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
copy nginx.conf /etc/nginx/nginx.conf
copy code /usr/share/nginx/html/