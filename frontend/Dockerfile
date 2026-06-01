FROM node:20

WORKDIR /app

COPY vue-project/package*.json ./

RUN npm install

COPY vue-project/ .

EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host"]