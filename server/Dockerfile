# Specify a base image
FROM node:alpine

# copy build files
WORKDIR /app
COPY ./package.json ./

# Install some dependencies
RUN npm install
COPY . .

# Default command
CMD ["npm","run","start"]