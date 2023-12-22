FROM node:20.10.0

WORKDIR /app

COPY package*.json .
ENV PORT 5000
COPY . .
RUN npm install
EXPOSE 5000
CMD [ "npm", "start" ]
