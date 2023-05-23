# Use an existing docker image as a base
FROM node:14-alpine

WORKDIR /usr/app

# Copy files from local fs into docker fs
# Install dependencies 
COPY ./package.json ./ 
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]