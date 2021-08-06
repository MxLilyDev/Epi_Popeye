FROM node:12-alpine

EXPOSE 80
ENV PORT=80

COPY . /result
WORKDIR /result

RUN npm install

CMD ["npm", "start"]
