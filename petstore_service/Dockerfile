FROM node:7
WORKDIR /usr/app
COPY package.json /usr/app
RUN npm install
COPY . /app
CMD node index.js
EXPOSE 3000:3000