FROM node:9.11.1-alpine

#RUN npm install -g http-server
#RUN npm install -g @vue/cli

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 8080

#CMD npm run build

#CMD ["http-server", "public"]
#CMD ["npm", "run", "serve"]
RUN npm run serve
