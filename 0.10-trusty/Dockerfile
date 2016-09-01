FROM bilxio/node:0.10-trusty

MAINTAINER haibxz@gmail.com

RUN npm install -g coffee-script pm2 forever

RUN apt-get update && apt-get install -y zip unzip

WORKDIR /app
VOLUME ["/srv", "/data", "/tmp", "/var/www", "/app"]
CMD ["coffee", "index.coffee"]

EXPOSE 8080 8443 9988 8989
