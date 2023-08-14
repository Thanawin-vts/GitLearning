# Use an official Node.js runtime as the base image
FROM node:14

# Set the working directory inside the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install Angular CLI and project dependencies
RUN npm install -g @angular/cli
RUN npm install

# Copy the rest of the application code to the container
COPY . .

# Build the Angular application
RUN ng build