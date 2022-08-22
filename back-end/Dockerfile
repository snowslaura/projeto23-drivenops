FROM node:16

WORKDIR /usr/src/

COPY . /usr/src/

RUN npm i
RUN npm run build

EXPOSE 5000


CMD ["npm", "run", "start"]