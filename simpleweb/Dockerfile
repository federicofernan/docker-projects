# Use an existing docker image as a base
FROM node:alpine
# Working Directory
WORKDIR /usr/app
# Copy files to image
COPY ./package.json ./
# Install npm dependencies
RUN npm install
# Copy files to image
COPY ./ ./
# Start the server
CMD ["npm","start"]