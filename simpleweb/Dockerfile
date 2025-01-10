# Base Image
FROM node:14-alpine

WORKDIR /usr/app

# Installing necessary dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Command required to run while starting the image
CMD ["npm", "start"]