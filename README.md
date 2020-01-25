# @react-corekit/sleep

> Non blocking asynchronous sleep. Due the nature of javascript an the event loops, it's only suspends the current function execution. It does not pause the entire program execution.

[![NPM](https://img.shields.io/npm/v/@react-corekit/sleep.svg)](https://www.npmjs.com/package/@react-corekit/sleep)

## Install

```bash
npm install --save @react-corekit/sleep
```

```bash
yarn add @react-corekit/sleep
```

## Syntax

```js
await sleep(n);
// Do something
```

```js
sleep(n).then(() => {
  // Do something
});
```
