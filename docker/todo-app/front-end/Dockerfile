FROM node:14-alpine

EXPOSE 3000

ADD node_modules.tar.gz .

WORKDIR /

COPY package-lock.json .
COPY package.json .
COPY .gitignore .
COPY src .
COPY public .
COPY README.md .

ENTRYPOINT [ "npm", "start" ]
