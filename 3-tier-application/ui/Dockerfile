FROM nginx:alpine

COPY . /usr/share/nginx/html

EXPOSE 80

RUN apk update && apk add --no-cache curl 

CMD ["nginx", "-g", "daemon off;"]
