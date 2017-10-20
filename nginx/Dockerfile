FROM nginx:alpine

MAINTAINER Makkhawan Voraboot

# Copy custom nginx config
COPY ./nginx/default.conf /etc/nginx/default.conf

EXPOSE 80 443

ENTRYPOINT ["nginx", "-g", "daemon off;"]
