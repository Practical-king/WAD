# docker build -t myapp .
# docker run -p 3000:3000 myapp
# open in browser http://localhost:3000

FROM node:18

WORKDIR /app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "app.js"]