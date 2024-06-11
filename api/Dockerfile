FROM node:17-alpine

RUN npm install -g nodemon

WORKDIR /app

# If I want to cache my json 
# COPY package.json . 
# RUN npm install 

COPY . .

RUN npm install

EXPOSE 4000
# required for docker desktop port mapping

CMD ["npm", "run", "dev"]