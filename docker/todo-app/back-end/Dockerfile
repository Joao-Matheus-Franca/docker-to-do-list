FROM node:14-alpine

EXPOSE 3001

ADD node_modules.tar.gz .

WORKDIR /

COPY package-lock.json .
COPY package.json .
COPY .gitignore .
COPY src .

ENTRYPOINT [ "npm", "start" ]