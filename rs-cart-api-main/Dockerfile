FROM node:12-alpine
COPY package*.json ./
RUN npm install
COPY * ./
RUN npm run build
EXPOSE 4000
CMD [ "node", "dist/main.js"]
