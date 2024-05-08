# Get the Node.js base Docker image --hared!
FROM node:carbon

# Set the directory to run our Docker command in
WORKDIR /app

# Copy your application source to this directory
COPY src .

# Start your application
CMD ["node", "/app/index.js"]