FROM node:16

# Create app directory
WORKDIR /usr/src/app

# Copy the package.json related files to working directory
# A wildcard is used to ensure both package.json AND package-lock.json are copied
COPY package*.json ./

# Install app dependencies
RUN npm install

# Bundle app source
COPY . .

# Expose port 3000
EXPOSE 3000

# Define the command to start application
CMD [ "node", "index.js" ]
