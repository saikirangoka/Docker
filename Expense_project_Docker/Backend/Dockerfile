FROM node:20
WORKDIR /opt/backend
COPY code/*.json .
COPY code/*.js .
RUN npm install
ENV DB_HOST="mysql"
CMD [ "node", "index.js" ]