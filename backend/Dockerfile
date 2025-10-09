FROM node:14.16.0-alpine3.13

RUN addgroup dev && adduser -S -G dev dev
USER dev

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . . 

EXPOSE 3001 

CMD ["npm", "start"]