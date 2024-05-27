FROM node:18.20

WORKDIR /usr/src/app

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "bash", "scripts/docker_run.sh" ]
