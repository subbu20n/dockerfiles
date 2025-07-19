FROM run:v1 
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://github.com/daws-84s/notes/blob/main/session-01.txt /usr/sharenginx/html/index.html 
RUN chmod +r /usr/share/nginx/html/index.html 
CMD ["nginx","-g","daemon off;"]