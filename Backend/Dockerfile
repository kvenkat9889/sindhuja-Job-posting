# Use the official Node.js image
FROM node:16

# Create app directory
WORKDIR /usr/src/app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Bundle app source
COPY . .

# Expose the port the app runs on
EXPOSE 3401

# Command to run the application
CMD ["node", "server.js"]
