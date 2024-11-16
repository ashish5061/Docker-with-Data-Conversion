# Use a lightweight image
FROM node:22.11.0-alpine

# Set working directory
WORKDIR /frontend

# Copy package.json and lock file first (to leverage caching)
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Default command
CMD ["npm", "run", "dev"]
