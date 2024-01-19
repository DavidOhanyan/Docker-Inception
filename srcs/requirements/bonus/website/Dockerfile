FROM debian:buster

RUN apt-get update -y && apt-get upgrade -y

RUN apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_lts.x | bash -
RUN apt-get install -y nodejs && rm -rf /var/lib/apt/lists/*

COPY ./tools /home/app

WORKDIR /home/app

RUN npm init -y && npm install express -y

EXPOSE 3000

CMD ["node", "server.js"]