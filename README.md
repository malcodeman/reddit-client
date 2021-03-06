# [Lurkershub](http://lurkershub.surge.sh)

[![Build Status](https://travis-ci.org/malcodeman/reddit-client.svg?branch=master)](https://travis-ci.org/malcodeman/reddit-client)
[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/malcodeman/micro-reddit/blob/master/LICENSE)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://github.com/prettier/prettier)
[![style: styled-components](https://img.shields.io/badge/style-%F0%9F%92%85%20styled--components-orange.svg?colorB=daa357&colorA=db748e)](https://github.com/styled-components/styled-components)

Lurkershub is content oriented reddit client which aims to show reddit images and videos in most efficient way possible.

![Screenshot](docs/images/screenshot.jpg)

## Getting started

First, clone and run the api:

```
git clone https://github.com/malcodeman/micro-reddit.git micro-reddit
cd micro-reddit
yarn install && yarn start
```

Next, you can clone and run the frontend:

```
git clone https://github.com/malcodeman/reddit-client.git reddit-client
cd reddit-client
yarn install && yarn start
```

.env.development.local:

```
REACT_APP_API_URL = "http://localhost:8080"
```

.env.production.local:

```
REACT_APP_API_URL = "https://malcodeman-micro-reddit.glitch.me"
```

## Design decisions

Why ... ?

- [react-intersection-observer](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)

## Credits

Huge ❤️ to:

- [Luis Merino](https://github.com/Rendez) for his work on react-intersection-observer

## Todos

- Improve post details modal
- Add comments
- Add bookmarks
- Add posts loadings state
- Add data import/export

## License

[MIT](./LICENSE)
