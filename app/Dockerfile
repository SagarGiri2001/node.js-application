FROM node:18-alpine

RUN apk add --no-cache python3 g++ make

WORKDIR /app

COPPY . .

RUN yarn install --production

CMD ["node", "src/index.js"]