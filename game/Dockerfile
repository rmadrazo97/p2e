# Use an official Node runtime as the base image
FROM node:14

# Set the working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install project dependencies
RUN npm install

# Copy the current directory contents into the container
COPY . .

# Make port 8080 available to the outside world
EXPOSE 8080

# Run the application
CMD ["npm", "start"]
