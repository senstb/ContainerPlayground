FROM ubuntu
RUN apt-get update
RUN apt-get install nginx -y
COPY index.html /var/www/html/
COPY login-page.css /var/www/html/
COPY login-page.js /var/www/html/
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
