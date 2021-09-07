FROM node:10.0.0-wheezy

RUN mkdir /web

WORKDIR /web

COPY . .

RUN npm i npm@latest -g

RUN npm install

ENV PORT=8080
ENV API_HOST=http://192.168.0.38:3000

EXPOSE 8080

CMD ["node", "./bin/www"]