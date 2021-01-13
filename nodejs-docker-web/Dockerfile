FROM node:10

# Create working directory
WORKDIR /usr/src/app

COPY package.json ./

RUN npm install

COPY ./ ./

CMD ["node" ,"server.js"] 