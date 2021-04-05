FROM nginx:1.19
EXPOSE 8080
RUN rm /etc/nginx/conf.d/default.conf
COPY conf/gitlab.conf /etc/nginx/conf.d/gitlab.conf
COPY conf/nginx.conf /etc/nginx/nginx.conf
CMD ["nginx"]