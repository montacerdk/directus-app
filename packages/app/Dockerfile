FROM node:slim

ARG PORT

WORKDIR /cms

COPY package.json .

RUN npm install --silent

COPY . .

EXPOSE $PORT

CMD ["npm", "start"]
