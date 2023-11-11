FROM nginx:alpine
RUN apk add shadow
RUN mkdir /app && \
    usermod -u 1001 nginx && \
    groupmod -g 1001 nginx
ADD nginx.conf /etc/nginx/nginx.conf
EXPOSE 8000

