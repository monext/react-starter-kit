# React Starter Kit

This is a React App boilerplate in JS. Uses Redux-Saga, flow typing, emotion, and jest unit tests.

## Getting Started

To build the project **node.js** and **npm** is required (I used node v14.15.3 and npm v6.14.9).

### Installing

After node and npm are ready, from the project's root folder run:

```
npm install
```

## Running the project

To start webpack dev server at [http://localhost:8080](http://localhost:8080) run:

```
npm run server
```

To build a development bundle with automatic rebuild on code changes:

```
npm run start
```

To build a minified production bundle:

```
npm run build
```

The build files are located in ```./dst``` folder.

## Running the project's flow validation check

To run flow validation check:

```
npm run flow
```

To run flow validation watch:

```
npm run flow:watch
```

## Running the project's eslint validation check

To run eslint validation check:

```
npm run eslint
```

## Running the project's unit tests

To run unit tests:

```
npm run test
```
