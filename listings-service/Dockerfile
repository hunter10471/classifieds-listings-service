FROM node:latest

COPY . /opt/app

WORKDIR /opt/app

RUN cd src && node index

CMD npm run watch