<h1 align="center">
  IVR

## Prerequisites

- [Node.js](https://nodejs.org/en/download/package-manager)
- [NPM](https://docs.npmjs.com/getting-started/installing-node)
- [Yarn](https://yarnpkg.com/en/docs/install)
- [Docker](https://www.docker.com/get-started/)

## Supbase 
```sh
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
```sh
$ cd ./nuxt
$ npm i # or yarn
$ npm run dev # or yarn dev
```

Navigate to http://localhost:3000 to access Nuxt.
