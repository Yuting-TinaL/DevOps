# Use an official Node runtime as a parent image
FROM node:18-slim

# Set the working directory in the container
WORKDIR /app

# Copy package.json and package-lock.json into the container
COPY package.json package-lock.json ./

# Install app dependencies
RUN npm install --production

# Copy the current directory contents into the container (excluding files in .dockerignore)
COPY . .

# Build the app (if a build step is necessary, e.g., for React, Vue, or other frameworks)
RUN npm run build

# Make port 3000 available to the world outside this container
EXPOSE 3000

# Define environment variable
ENV NODE_ENV=production

# Run the app when the container launches
CMD ["npm", "start"]