FROM node:16

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
# If you are building your code for production
# RUN npm ci --only=production


# copy all files into the image
COPY . .

EXPOSE 5000

CMD ["npm", "run", "server"]