FROM node:16

WORKDIR /app

EXPOSE 5000

COPY package.json package-lock.json ./

ENV REACT_APP_BACKEND_URL=http://localhost:8080/

RUN npm install

COPY . .

RUN npm run build

RUN npm install -g serve

CMD ["serve", "-s", "-l", "5000", "build"]
