ARG TAG=1.19
FROM nginx:$TAG
EXPOSE 80
RUN rm /etc/nginx/conf.d/default.conf
COPY conf/nginx.conf /etc/nginx/nginx.conf
COPY conf/gitlab.conf /etc/nginx/conf.d/gitlab.conf
COPY conf/jenkins.conf /etc/nginx/conf.d/jenkins.conf
CMD ["nginx"]