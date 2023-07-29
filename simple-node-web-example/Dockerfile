# Specify a base image
# FROM alpine
FROM node:14-alpine

WORKDIR /usr/app

#install some depenendicies
COPY ./ ./
RUN npm install

# Defautl command
CMD ["npm","start"]
