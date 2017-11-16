FROM ionic-fastlane:1.0

MAINTAINER Vinicius Viale Pinheiro

COPY . /futuro-app
WORKDIR /futuro-app
RUN npm install && \
ionic cordova platform add android

EXPOSE 8100 35729

CMD ["ionic", "serve"]
