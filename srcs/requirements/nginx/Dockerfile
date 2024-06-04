FROM debian:bullseye
RUN apt-get update && apt-get install -y nginx openssl
EXPOSE 443
COPY ./conf/default /etc/nginx/sites-enabled/
COPY ./tools/nginxstart.sh /
RUN chmod +x /nginxstart.sh
ENTRYPOINT [ "/nginxstart.sh" ]
CMD [ "nginx", "-g", "daemon off;" ]