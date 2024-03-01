FROM node:19

WORKDIR /my-react-app

COPY . /my-react-app/

RUN npm install

RUN npm run build

EXPOSE 3000

CMD ["npm", 'start']