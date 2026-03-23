FROM node:16-alpine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the full project source
COPY . .

# Expose the app's port
EXPOSE 5000

# Command to run your Node.js app	
CMD ["node", "./src/server.js"]