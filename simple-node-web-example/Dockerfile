# Specify a base image
# FROM alpine
FROM node:14-alpine

WORKDIR /usr/app

#install some depenendicies
COPY ./package.json ./
RUN npm install

COPY ./ ./

# Defautl command
CMD ["npm","start"]
