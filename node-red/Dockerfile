FROM node:10.15-alpine

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
COPY ./package*.json /usr/src/app/
RUN npm install --silent
COPY . /usr/src/app
EXPOSE 1880
CMD ["npm", "start"]
