# Specify a base image
FROM node:alpine

# Create working directory
WORKDIR /app

# Include directory files, frist package.json after npm rest
COPY ./package.json ./

# Install some dependencies
RUN npm install

COPY ./ ./

# Default command
CMD ["npm", "start"]