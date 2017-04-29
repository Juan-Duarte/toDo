FROM node:boron

# Create app directory
RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app

RUN npm install -g json-server

# Bundle app source
COPY . /usr/src/app

CMD ["json-server", "--watch", "db.json"]