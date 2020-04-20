FROM node:12-stretch

LABEL maintainer="suisrc@outlook.com"

RUN npm install --production -g cnpm --registry=https://registry.npm.taobao.org &&\
    npm config set registry https://registry.npm.taobao.org --global &&\
    npm config set disturl https://npm.taobao.org/dist --global
