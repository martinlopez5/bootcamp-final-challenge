FROM nginx:alpine

RUN apk add --no-cache jq curl

EXPOSE 3000
EXPOSE 3002

COPY docker-deps/default.conf /etc/nginx/conf.d/default.conf

