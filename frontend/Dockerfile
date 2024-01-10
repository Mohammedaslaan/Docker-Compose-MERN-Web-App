FROM node

LABEL Name="Mohammed"

WORKDIR /app

COPY package.json /app/

RUN npm install

VOLUME [ "/app/node_modules" ]

COPY . .


CMD [ "npm","start" ]