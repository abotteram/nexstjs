# Use the official Node.js 14 image as the base image
FROM node:18-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the package.json and yarn.lock files to the working directory
COPY package.json yarn.lock ./

# Install the dependencies using Yarn
RUN yarn install

# Expose the port that the Next.js app will run on
EXPOSE 3000

# Start the Next.js app
CMD ["yarn", "dev"]
