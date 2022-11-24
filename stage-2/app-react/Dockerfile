FROM node:19-alpine3.15

WORKDIR /usr/src/app

#copy source code to working directory
COPY . .

#install dependencies
RUN npm install
RUN npm run build


EXPOSE 3000

#start app
CMD ["npm", "start"]