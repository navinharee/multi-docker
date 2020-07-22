FROM node:alpine

WORKDIR '/app'

COPY ./package.json ./

RUN npm install

COPY . .

# run the below start up command
CMD ["npm","run","start"]