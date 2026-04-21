FROM node:20-alpine
WORKDIR /app
COPY code/*.js /app/
COPY code/*.json /app/
RUN npm install
ENV MONGO="true"
ENV REDIS_URL='redis://redis:6379'
ENV MONGO_URL="mongodb://mongodb:27017/users"

CMD [ "node","server.js" ]