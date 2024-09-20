#Use the official Node.js image
FROM node:20

#Set the working directory in the container
WORKDIR /usr/src/app

#Install app dependencies
COPY package*.json ./
RUN npm install

#Copy the rest of your application code
COPY . .

#Expose the port your app will run on
EXPOSE 3030

#Command to run your app
CMD [ "npm", "start" ]

