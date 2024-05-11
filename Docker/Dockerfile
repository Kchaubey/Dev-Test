FROM node:14-alpine

# Set working directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json if your app requires them
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of your application code
COPY . .

# Expose the port your app runs on
EXPOSE 3000

# Command to run your application
CMD ["node", "index.js"]
