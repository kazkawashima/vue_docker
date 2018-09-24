# vue_docker

## Quick Start

Create docker container.

```shell
$ docker-compose -f docker-compose.yml up -d --build
```

Into docker container.

```shell
$ docker exec -it CONTAINER /bin/sh
```

```shell
$ firebase login
```
or
```shell
$ firebase login:ci --no-localhost
```

Create Vue.js project with Nuxt.js

```
$ vue init nuxt-community/starter-template
```

`yarn install` and `yarn run dev`.

```
$ yarn install
$ yarn run dev
```

If prepare done, access http://localhost:3000

Enjoy your Vue.js :)


added from original

./docker/node/Dokcerfile
npm -g firebase-tools

./docker-compose.yml
-p "9005:9005"
