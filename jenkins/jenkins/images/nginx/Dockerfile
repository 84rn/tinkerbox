FROM nginx:1.19
EXPOSE 8080
RUN rm /etc/nginx/conf.d/default.conf
COPY conf/jenkins.conf /etc/nginx/conf.d/jenkins.conf
COPY conf/nginx.conf /etc/nginx/nginx.conf
CMD ["nginx"]