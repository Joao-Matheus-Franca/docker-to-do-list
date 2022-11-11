FROM node:14-alpine

EXPOSE 3001

ADD node_modules.tar.gz .

COPY package-lock.json .
COPY package.json .
COPY .gitignore .
COPY src .

ENTRYPOINT [ "npm", "start" ]