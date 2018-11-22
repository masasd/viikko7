FROM node:10
WORKDIR /osa5
COPY package.json ./
RUN npm install
COPY . /osa5
EXPOSE 3000
CMD ["npm", "start"]
