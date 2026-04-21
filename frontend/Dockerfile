FROM nginx:1.28.3
WORKDIR /app
RUN rm -rf /usr/share/nginx/html/*    && \
    rm -rf /etc/nginx/conf.d/*.conf
COPY code/ /usr/share/nginx/html/
COPY nginx.conf  /etc/nginx/nginx.conf
