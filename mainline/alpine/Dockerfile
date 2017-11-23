FROM alpine:3.6.2

RUN apk add --update nginx && rm -rf /var/cache/apk/*

CMD ["nginx", "-g", "daemon off;"]
