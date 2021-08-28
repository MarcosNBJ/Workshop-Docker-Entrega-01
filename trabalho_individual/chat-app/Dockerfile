FROM node:16-alpine
WORKDIR /app
COPY package.json /app
RUN yarn
COPY . /app
EXPOSE 7001
CMD ["yarn", "watch"]