FROM node:16.16.0-alpine
WORKDIR /app
COPY ./package.json ./package.json
COPY .  .
RUN yarn install
EXPOSE 5000

CMD ["yarn","start"]
