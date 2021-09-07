FROM node:10.0.0-wheezy

RUN mkdir /api

WORKDIR /api

COPY . .

RUN npm i npm@latest -g

RUN npm install

EXPOSE 2999

CMD ["node", "./bin/www"]