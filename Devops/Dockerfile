# FROM node:12.18.1
FROM node:10-alpine
# creating the working directory.
WORKDIR /app
# COPY: this will copy the whole directory to /app folder.(Assignment3).
COPY package*.json ./ 
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "node", "app.js" ]