# Use an official Node runtime as a parent image
FROM node:lts

# Set the working directory in the container
WORKDIR /usr/src/app

# Install Docsify CLI globally
RUN npm install -g docsify-cli

# Expose the port the app runs on
EXPOSE 3000

# Start Docsify when the container launches
CMD ["docsify", "serve", "."]
