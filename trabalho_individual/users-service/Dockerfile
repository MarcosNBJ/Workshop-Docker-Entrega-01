FROM node:16-alpine
WORKDIR /app
COPY package.json /app
RUN yarn
COPY . /app
EXPOSE 7101
CMD ["yarn", "watch"]