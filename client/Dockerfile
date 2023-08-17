FROM node:13.12.0 alpine3
RUN mkdir -p app
WORKDIR /app
COPY . /app
RUN npm install
EXPOSE 3000
CMD [ "npm", "start" ]