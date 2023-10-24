from node:alpine

workdir /time-app

copy package*.json ./

run npm install

copy . .

expose 5000

cmd ["npm","run","dev"]