# Micro-frontends with Web Components

Example of using web components as a wrapper for both Angular and React components.

## Build and serve Angular component

```sh
cd micro-fe-ng
npm i
npm start
```
[http://localhost:5001/main.js](http://localhost:5001/main.js)

```html
<ng-el></ng-el>
```

## Build and serve React component

```sh
cd micro-fe-react
npm i
npm start
```
[http://localhost:5002](http://localhost:5002)


```html
<react-el></react-el>
```

## Build and serve wrapper

```sh
cd micro-fe-wrapper
npm i
npm start
```
[http://localhost:5000](http://localhost:5000)

Special thanks to [@kitson.mac](https://medium.com/@kitson.mac/create-micro-frontends-using-web-components-with-support-for-angular-and-react-2d6db18f557a?source=friends_link&sk=642e86f203d58724d63d9d98aeb11476).
