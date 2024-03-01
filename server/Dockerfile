FROM node:19

WORKDIR /server

COPY . /server/

RUN npm install

RUN npm run build

EXPOSE 3003

CMD ["npm", 'start']