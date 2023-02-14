FROM node:14-alpine
EXPOSE 3001
WORKDIR /
COPY . .

RUN npm install
ENTRYPOINT [ "npm", "start"]
