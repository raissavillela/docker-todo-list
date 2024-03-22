FROM node:16-alpine

EXPOSE 3001

WORKDIR /app/back-end

ADD node_modules.tar.gz .

COPY . /app/back-end

ENTRYPOINT [ "npm" ]

CMD [ "start "]