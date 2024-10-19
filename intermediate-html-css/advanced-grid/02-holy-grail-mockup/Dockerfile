FROM alpine:latest
RUN apk add --no-cache nodejs npm
RUN npm install -g live-server
WORKDIR /app
EXPOSE 5510
ENTRYPOINT ["live-server", "--host=0.0.0.0", "--port=5510", "--watch=."]
