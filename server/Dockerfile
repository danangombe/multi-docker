FROM node:alpine
#Love this to bits

WORKDIR "/app"

COPY ./package.json ./


RUN npm install


COPY .  .


CMD ["npm","run","start"]