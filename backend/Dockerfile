FROM node:current-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install

# Copy source code
COPY . .

EXPOSE 3000

CMD ["npm","run", "dev"]
