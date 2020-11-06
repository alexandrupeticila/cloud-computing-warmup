FROM node:15

#create app directory
WORKDIR /usr/src/app

#copy dependecy files
COPY package*.json ./

#install dependencies
RUN npm install

#bundle app source
COPY . .

CMD ["node", "start.js"]
