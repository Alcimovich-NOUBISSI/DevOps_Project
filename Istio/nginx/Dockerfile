FROM nginx:1.16.1
COPY . /usr/share/nginx/html
RUN apt-get update && apt-get install inetutils-ping -y
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]