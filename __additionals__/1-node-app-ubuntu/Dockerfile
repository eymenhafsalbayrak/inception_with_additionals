FROM ubuntu:18.04
RUN apt-get update
RUN apt-get install curl -y
RUN curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
RUN apt-get install nodejs -y
WORKDIR /opt/node-app
COPY . /opt/node-app/
ENV channel=eyms
CMD ["node", "index.js"];