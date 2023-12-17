FROM node:14

WORKDIR /app

RUN npm install typescript --save-dev

COPY . /app

RUN npm install

CMD ["npm", "run", "dev"]