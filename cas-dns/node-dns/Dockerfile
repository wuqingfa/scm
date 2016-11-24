FROM node

COPY ./src/dns-server/ /app

WORKDIR /app
RUN npm install

EXPOSE 53/udp 53/tcp
CMD ["npm","start"]
