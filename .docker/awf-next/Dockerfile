FROM node:16-alpine

RUN mkdir -p /usr/src/app 

WORKDIR /usr/src/app

COPY ./next-app/package.json /usr/src/app/

RUN yarn

EXPOSE 3000

CMD ["yarn", "dev"]