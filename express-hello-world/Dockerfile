FROM node:12.14.1-alpine
EXPOSE 3001
WORKDIR /home/app

COPY express-hello-world/package.json /home/app/
COPY express-hello-world/package-lock.json /home/app/
RUN npm install

COPY . /home/app

CMD ["npm", "run", "start"]
