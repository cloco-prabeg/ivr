<h1 align="center">
  IVR

## Prerequisites

- [Node.js](https://nodejs.org/en/download/package-manager)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)
- [Yarn](https://yarnpkg.com/en/docs/install)
- [Docker](https://www.docker.com/get-started/)

## Supbase 
```https://github.com/cloco-prabeg/ivr
$ cd ./supabase/docker
$ cp .env.exmaple .env
$ docker compose pull
$ docker compose up -d
```

Navigate to http://localhost:8000 to access Supabase Studio.

You will be prompted for a username and password. By default, the credentials are:

Username: supabase
Password: this_password_is_insecure_and_should_be_updated

For more info on setup visit: https://supabase.com/docs/guides/self-hosting/docker

## Nuxt
Running nuxt locally
```sh
$ cd ./nuxt
$ npm i # or yarn
$ npm run dev # or yarn dev
```

Running nuxt via docker
```sh
$ cd ./nuxt
$ docker build -t ivr:1 .
$ docker run --name ivr_nuxt -v $(pwd):/home/ivr --user $(id -u):$(id -g) -p 3000:3000 ivr:1
```

To run commands inside docker container
```sh
$ docker run -it ivr_nuxt /bin/bash
```

Navigate to http://localhost:3000 to access Nuxt.
