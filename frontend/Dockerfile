FROM node:22.22.0-alpine

WORKDIR /app

COPY . /app/

RUN npm install

EXPOSE 8080
CMD ["npm", "run", "dev"]