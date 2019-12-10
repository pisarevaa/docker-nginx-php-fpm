FROM nginx:1.17.6-alpine

LABEL maintainer="Pisarev Andrey <pisarev_aa@mail.ru>"

COPY nginx.conf /etc/nginx/
COPY default.conf /etc/nginx/conf.d

RUN apk update \
    && apk upgrade \
    && apk add --no-cache nano

EXPOSE 80 443