FROM nginx:1.15-alpine
COPY ./nginx.conf /etc/nginx/nginx.conf
COPY ./uwsgi_params /uwsgi_params
CMD ["nginx", "-g", "daemon off;"]