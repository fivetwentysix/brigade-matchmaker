FROM alpine:3.7

RUN apk add --update nodejs nodejs-npm git python alpine-sdk
RUN npm -g install yarn
RUN mkdir /app
WORKDIR /app
VOLUME /app
CMD ["yarn"]
