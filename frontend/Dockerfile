#Pull the Image
FROM node:18-alpine
#Create the work directory
WORKDIR /app
#copy dependencies
COPY package*.json ./
#run installation
RUN npm install
#copy the remaining programm files to the container
COPY . .
#expose the port
EXPOSE 2000
#run the backend application- this is on React
CMD [ "npm", "start" ]