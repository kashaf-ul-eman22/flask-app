FROM node:22
WORKDIR /flask
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3001
CMD ["npm" , "start"]

