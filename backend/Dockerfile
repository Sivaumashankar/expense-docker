FROM node:20
WORKDIR /app
COPY package.json .
RUN npm install
COPY *.js .
ENV DB_HOST="mysql"
CMD [ "node" ,"index.js" ]