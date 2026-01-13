FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

COPY . .

# Optional: logs folder inside container
RUN mkdir -p /app/logs

EXPOSE 5173
CMD ["npm","run","dev","--","--host"]
