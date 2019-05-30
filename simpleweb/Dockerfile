# Specify base image
FROM node:alpine

# Install some dependenciesß
WORKDIR /usr/app
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]