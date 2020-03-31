FROM node:alpine
WORKDIR /usr/fibonacci-app/
COPY ./package.json ./
RUN npm install
COPY . .
CMD npm run start

