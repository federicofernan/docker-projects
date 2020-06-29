# Use an existing docker image as a base
FROM node:alpine
# Define Working Directory
WORKDIR '/app'
# Copy package. json and Install npm dependencies
COPY package.json .
RUN npm install
COPY . .
# Start the server
CMD ["npm", "start"]