FROM mjgargani/puppeteer:trybe1.0

ADD node_modules.tar.gz .

WORKDIR /

COPY package-lock.json .
COPY package.json .
COPY jest.config.js .
COPY e2e .

ENTRYPOINT [ "npm", "test" ]
