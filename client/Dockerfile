FROM node:16.13.1

COPY . /app

ENV APIURL="test"

RUN npm config set strict-ssl false

RUN npm i --save @microsoft/signalr

CMD ["npm", "start"]
