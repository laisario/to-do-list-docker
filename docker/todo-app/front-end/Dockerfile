FROM node:14-alpine
EXPOSE 3000
WORKDIR /
COPY . .

RUN npm install
ENTRYPOINT [ "npm", "start"]

