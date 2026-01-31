# Use Node.js base image
FROM node:18-alpine

# Set working directory inside the container
WORKDIR /usr/src/app

# Copy all source files into the container
COPY . .

# Install express directly (since no package.json is present)
RUN npm install express

# Expose the port your app listens on
EXPOSE 3000

# Run the application
CMD ["node", "src/index.js"]
