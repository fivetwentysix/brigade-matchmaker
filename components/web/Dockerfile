FROM node:6.12.2-alpine

RUN apk add --update git python alpine-sdk
RUN npm -g install yarn
RUN mkdir /app
VOLUME /app
WORKDIR /app
COPY . /app
RUN yarn --pure-lockfile
CMD ["yarn"]
