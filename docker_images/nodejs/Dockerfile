# Use the official Node.js image as a base image
FROM node:lts

# Set the working directory in the container
WORKDIR /app/data

# Copy the package.json file to the working directory
COPY package.json .

# Install dependencies
RUN npm install

# Set the environment variable START for the container
ENV START="npm start"

# Run the command specified in START
CMD ["sh", "-c", "$START"]
