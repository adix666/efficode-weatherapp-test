FROM node:14-alpine
EXPOSE 9000
COPY . /app
WORKDIR /app
RUN npm install && npm build
CMD ["npm", "start"]