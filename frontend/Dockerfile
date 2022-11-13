FROM node:14-alpine
EXPOSE 9001
COPY . /app
WORKDIR /app
RUN npm install && npm build
CMD ["npm", "start"]