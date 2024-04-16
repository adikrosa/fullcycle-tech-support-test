FROM node:18-slim

WORKDIR /usr/src/app

EXPOSE 3000

RUN npm install -g nodemon

ENTRYPOINT ["nodemon", "/usr/src/app"]

CMD ["npm", "run", "dev"]