FROM node:14

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

ARG PORT_DEFAULT=80

ENV PORT=$PORT_DEFAULT

EXPOSE $PORT

# VOLUME [ "/app/feedback" ]

CMD ["npm", "start"]


