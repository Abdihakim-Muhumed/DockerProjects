#######################################
# Dockerfile to build a sample web application
#######################################

#Base image is node.js
FROM node:latest

#Author: Moringa School
LABEL maintainer="Moringa School <moringaschool.com>"

#Install redis driver for node.js
WORKDIR /myapp
RUN npm install redis
COPY . .
#Copy the source code to the Docker Image
ADD composeHelper.js /myapp/composeHelper.js
