# Universal Demonstration of [Redux-First Router](https://github.com/faceyspacey/redux-first-router) with [html-webpack-plugin](https://github.com/jantimon/html-webpack-plugin) and [ejs](https://github.com/mde/ejs)

This is only an extend or alternative version of James Gilmore's amazing

## Installation

```
git clone https://github.com/martiuh/refiro-with-ejs
cd refiro-with-ejs
yarn
yarn start
```
#### Watch the app running in Heroku
#### [`https://refiro-with-ejs.herokuapp.com`](https://refiro-with-ejs.herokuapp.com)

## What it makes?

##### Because it's only a version of [`redux-first-router-demo`](https://github.com/faceyspacey/redux-first-router-demo), you can find all the dazzling features it has.

- **Server Side Rendering**
- **Code splitting**
- **Redux First Router** a really simple and powerful router
- **Universal code**
- [**... And many other features**](https://github.com/faceyspacey/redux-first-router-demo)

### What is new then?

Well I just grabbed the demo and add it support to html-webpack-plugin that allow to inject certain webpack output chunks into my `render.ejs` so I can easily just inject my vendor.js (which was not posible in the demo) also it's possible to use a lot of html-webpack-plugin compatible plugins, in this repo I have support for [`favicons-webpack-plugin`](https://github.com/jantimon/favicons-webpack-plugin) which allows us to inject all the favicons related tags and also some PWA-ish functions.
