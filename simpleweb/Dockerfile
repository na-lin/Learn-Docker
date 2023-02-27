# Basic image
FROM node:14-alpine

# specify working directory
WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./
# setup command
CMD ["npm","start"]
