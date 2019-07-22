# A docker image for web font-end development and continue integrations.

## Dependences

- node.js@10.16.0
- yarn@1.16.0
- npm@6.9.0
- rsync@3.1.2

## Usage

- You can use my image repository directly.

```shell
docker pull chenkang0503/front-end-env:latest
```

- Build a new image for yourself.

```shell
docker build -t YOUR_IMAGE_NAME:TAG_NAME ./web-env
```

## Upgrade

1. Open `Dockerfile` and modify `ENV NODE_VERSION` and `ENV YARN_VERSION` to new version.
2. Build image.
