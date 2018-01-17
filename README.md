# todo

todo

## INSTALLATION

```bash
$ git clone <git repo>
$ cd todo
$ npm i
```

## Run Webpack Dev Server on Local Environment

```bash
$ npm run dev // open http://localhost:3000
```

## Run Tests

```bash
$ npm test # Run test with Mocha under src/**/__specs__/*.js
$ npm run coverage # Run test with Coverage
```

## Build Client

```bash
$ npm run build (Environment Variable PROFILE is needed)
```

## Launch Stand Alone Server

```bash
$ npm start
```

## Run with Local Docker

```bash
$ npm run docker -- $npm script you want to run
$ npm run docker -- sh # Access to docker container with shell
$ npm run docker -- npm install
$ npm run docker -- npm run dev
```

**NOTE:** If you want to run npm scripts with docker, you should remove existing `node_modules`.
