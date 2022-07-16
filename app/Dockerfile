FROM node:16-alpine
WORKDIR /usr/src/app
RUN npm install express mysql
COPY ./server.js ./server.js
EXPOSE 8080 
CMD ["node", "server.js"]