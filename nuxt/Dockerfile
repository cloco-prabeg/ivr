FROM node:lts-bullseye

WORKDIR /home/ivr

COPY package* .

RUN npm i

COPY . .

EXPOSE 3000

CMD [ "npm", "run", "dev"]
