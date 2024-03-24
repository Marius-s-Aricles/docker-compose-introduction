FROM node:18-alpine

WORKDIR /app

COPY package.json .

RUN npm install

# Install Vite
RUN npm install vite@latest -g

COPY . .

EXPOSE 5173

CMD [ "npm", "run", "dev" ]