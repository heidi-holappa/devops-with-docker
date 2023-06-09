# BUILD: docker build . -t example-frontend
# RUN: docker run -p 3000:5000 example-frontend

FROM node:16

WORKDIR /usr/src/app

COPY . . 

RUN npm install

RUN npm run build

RUN npm install -g serve

EXPOSE 5000

CMD ["serve", "-s", "-l", "5000", "build"]
