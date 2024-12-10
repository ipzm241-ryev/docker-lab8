FROM node:20-alpine3.17
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install && npm install -g nodemon
COPY . .
EXPOSE 3001
CMD ["npm", "run", "dev"]
