FROM node

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 5000

ENV MONGODB_USERNAME=asif
ENV MONGODB_PASSWORD=secret

CMD ["npm","start"]