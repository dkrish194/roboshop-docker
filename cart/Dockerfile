FROM node:20
WORKDIR /app
COPY *.json *.js /app/
RUN npm install 
ENV REDIS_HOST=redis \
    CATALOGUE_HOST=catalogue \
    CATALOGUE_PORT=8080
CMD [ "node","server.js" ]