# Base Image 

FROM node:alpine

# Install dependencies
WORKDIR = /abhinav_code

COPY ./package.json ./

RUN npm install

COPY ./ ./

# Startup command
CMD ["npm", "start"]