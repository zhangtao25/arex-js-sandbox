# arex-js-sandbox

This package deals with providing a JavaScript sandbox for executing various security sensitive external scripts.

## How does this work?

This package makes use of [quickjs-emscripten](https://www.npmjs.com/package/quickjs-emscripten) for building sandboxes for running external code on Arex.

Currently implemented sandboxes:
- Arex Test Scripts
- Arex Pre Request Scripts

## Development

1. Clone the repository

```
git clone https://github.com/zhangtao25/arex-js-sandbox
```

2. Install the package dependencies

```
npm install
```


3. Try out the demo [`src/demo.ts`](https://github.com/zhangtao25/arex-js-sandbox/blob/main/src/demo.ts) using:

```
npm run demo
```