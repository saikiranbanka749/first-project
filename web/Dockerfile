FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d/default.conf.template
COPY default.conf.template /etc/nginx/nginx.conf
ADD static /usr/share/nginx/html/
ENV CATALOGUE_HOST="catalogue"
