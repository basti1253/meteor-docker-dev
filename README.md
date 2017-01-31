# meteor-docker-dev
dev runtime when meteor isn't available on your server

## environment variables

- USER: default "node"
- USERID: default "1000": change to UID of your user running this container
- PORT: meteor listening port, default 3000
- METEOR_VERSION: 1.4.2.3

usage example: check docker-compose.yml (you have to check container name and host path of your app)