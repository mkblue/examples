# neon-examples

![Github Actions](https://github.com/amilajack/neon-hello/workflows/Test/badge.svg?branch=master)

## Table of Contents

|  | Example | Descrption |
| --- | --- | --- |
| 1.|  [hello world](https://github.com/neon-bindings/examples/tree/master/hello-world) | Return a hello world string to Node |
| 2.|  [primitives](https://github.com/neon-bindings/examples/tree/master/primitives) | Creating JS primitives in Rust |
| 3.|  [arrays](https://github.com/neon-bindings/examples/tree/master/arrays) | Creating and using JS arrays in Rust |
| 4.|  [objects](https://github.com/neon-bindings/examples/tree/master/objects) | Creating and using JS objects in Rust |
| 5.|  [arguments](https://github.com/neon-bindings/examples/tree/master/arguments) | Getting and checking function arguments |
| 6.|  [functions](https://github.com/neon-bindings/examples/tree/master/functions) | Creating and calling JS functions from Rust |
| 7.|  [classes](https://github.com/neon-bindings/examples/tree/master/classes) | Creating classes |
| 8.|  [class factory](https://github.com/neon-bindings/examples/tree/master/class-factory) | Creating classes from a class. Useful for resource pools. |
| 9.|  [modules](https://github.com/neon-bindings/examples/tree/master/modules) | Exporting functions, classes, and values |
| 10.|  [json](https://github.com/neon-bindings/examples/tree/master/json) | Handling JSON passed between JS and Rust |
| 11.|  [errors](https://github.com/neon-bindings/examples/tree/master/errors) | Creating and throwing errors |
| 12.|  [async](https://github.com/neon-bindings/examples/tree/master/async) | Creating and scheduling async background tasks in Node's thread pool |
| 13.|  [thread count](https://github.com/neon-bindings/examples/tree/master/thread-count) | Expose the `num_cpus` Rust library to JS | 
| 14.|  [fibonacci async task](https://github.com/neon-bindings/examples/tree/master/fibonacci-async-task) | Computing the nth fibonacci number in Rust and passing the result to JS |
| 15.|  [word counting](https://github.com/neon-bindings/examples/tree/master/word-counting) | A word counting demo in Rust and JS with benchmarks |
| 16.|  [sharing binary data](https://github.com/neon-bindings/examples/tree/master/sharing-binary-data) | Handling binary data passed from Node to Rust |
| 17.|  [electron app](https://github.com/neon-bindings/examples/tree/master/electron-app) | A simple electron app using Neon modules |
| 18.|  [publishing modules](https://github.com/amilajack/disk-utility) | Using [`node-pre-gyp`](https://github.com/mapbox/node-pre-gyp) to build and publish binaries for multiple platforms |
| 19.|  [event emitter](https://github.com/neon-bindings/examples/tree/master/event-emitter) | An example of creating an `EventEmitter` with Neon |
| 20.|  [workspace](https://github.com/neon-bindings/examples/tree/master/workspace) | An example of using Neon in a Cargo workspace |
| 21.|  Bindgen | Planned |

## Setup

```bash
git clone https://github.com/neon-bindings/examples
cd neon-examples
yarn

# Compile and run an example:
cd primitives
node ./lib/index.js
```
