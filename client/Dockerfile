# Base Image
FROM node:alpine
ENV CI=true

# Set working directory
WORKDIR /app

#Copy package.json
COPY ./package.json ./

#install dependencies
RUN npm i

# Copy files
COPY ./ ./

# Default command
CMD [ "npm", "start" ]