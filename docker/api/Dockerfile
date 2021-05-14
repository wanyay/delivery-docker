FROM node:alpine

WORKDIR /app

COPY ["./api/package.json", "./api/package-lock.json"]

RUN npm install

COPY ./api .

EXPOSE 8080
CMD [ "npm", "run", "start" ]