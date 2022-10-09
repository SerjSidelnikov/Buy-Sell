FROM node:16-alpine

WORKDIR /frontend

COPY package*.json ./

RUN npm install --frozen-lockfile

COPY . .

CMD ["npm", "run", "dev"]