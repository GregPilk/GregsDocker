# Use the base image with Node.js installed
FROM node:14

# Set the working directory inside the container
WORKDIR /app

# Copy the package.json and package-lock.json files to the working directory
COPY package*.json ./

# Install the dependencies
RUN npm install

# Copy the rest of the application code to the working directory
COPY . .

# Expose port 8080
EXPOSE 8080

# Start the server
CMD [ "npm", "start" ]