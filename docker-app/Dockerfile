FROM node:16.14.2

RUN mkdir -p /app
WORKDIR /app
COPY package*.json /app
RUN npm i
COPY . /app
# RUN npm run build --prod

#! modo local
EXPOSE 4200
CMD ["npm", "run", "start:local"]
