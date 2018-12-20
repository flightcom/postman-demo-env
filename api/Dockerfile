FROM node:11

# Create app directory
WORKDIR /usr/src/app

# Install app dependencies
RUN npm install

# If you are building your code for production
# RUN npm install --only=production

# Bundle app source
COPY . .

EXPOSE 8080
CMD [ "npm", "run", "dev" ]
