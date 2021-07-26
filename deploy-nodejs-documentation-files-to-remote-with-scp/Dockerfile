FROM node:14

WORKDIR /home/user/custom-folder

COPY package*.json ./

RUN npm install

COPY . .

CMD [ "npm", "start" ]
