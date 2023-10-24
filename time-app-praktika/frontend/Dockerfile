from node:alpine

workdir /time-app

copy package*.json ./

run npm install

copy . .

expose 8954

cmd ["npm","run","dev"]