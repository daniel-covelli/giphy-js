![GIPHY for developers](./header.gif)

The GIPHY SDKs let you and your users easily access the world’s largest GIF library anywhere on your website. Whether it’s via a comment, forum post, review, chatbot or messenger, adding GIFs to your product is a simple and easy way to boost engagement and user experience.

## GIPHY-JS

[![Build Status](https://travis-ci.com/Giphy/giphy-js.svg?token=jJjbVBEbrqabxuHRjdmS&branch=master)](https://travis-ci.com/Giphy/giphy-js)

Choose your flavor!

### [@giphy/react-components](packages/react-components/README.md)

> React components focused on ease-of-use and performance

### [@giphy/js-components](packages/components/README.md)

> lightweight UI components

### [@giphy/js-fetch-api](packages/fetch-api/README.md)

> fetch gifs, stickers, categories and more and build your own UI

### Install

```sh
$ yarn && lerna bootstrap
```

### Dev

Some packages have

```sh
$ cd packages/components
$ yarn run dev
```

### Lint

From root of project:

```sh
$ yarn run lint
```

### Publishing

```sh
$ lerna version
```

[Travis](https://travis-ci.com/Giphy/giphy-js) will publish to npm
