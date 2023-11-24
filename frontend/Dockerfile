# Use an official Node.js runtime as a base image
FROM node:20

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY ./client/package*.json ./
COPY ./client/* ./

# Install dependencies
RUN npm install

# Copy the client directory to the working directory

# Expose the port the app runs on
EXPOSE 5173
# Command to run your application
CMD ["npm", "run", "dev"]
