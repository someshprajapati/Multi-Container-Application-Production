# Specify a base image
FROM node:alpine

# Specify a working directory
WORKDIR '/app'

# Install some depenendencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "run", "start"]