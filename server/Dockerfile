FROM node:25.5.0-alpine3.23
WORKDIR "/usr/app"
COPY ./package.json ./
RUN npm config set unsafe-perm true
RUN npm install
COPY . .
CMD ["npm", "run", "start"]