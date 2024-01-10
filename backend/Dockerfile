FROM node

LABEL Name="Mohammed"

WORKDIR /app

COPY package.json .

RUN npm install

VOLUME [ "/app/node_modules" ]

COPY . .

EXPOSE 80

CMD [ "npm","start" ]