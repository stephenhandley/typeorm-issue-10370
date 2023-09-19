Reproduction for this [typeorm issue](https://github.com/typeorm/typeorm/issues/10370)

```
yarn
yarn start
```


```
$ yarn start
yarn run v1.22.17
$ electron-forge start
✔ Checking your system
✔ Locating application
✔ Loading configuration
✔ Preparing native dependencies: 1 / 1 [0.1s]
✔ Running generateAssets hook
⠋ [plugin-vite] Launching dev servers for renderer process code
⠙ [plugin-vite] Launching dev servers for renderer process code
◼ [plugin-vite] Compiling main process code
✔ [plugin-vite] Launching dev servers for renderer process code [0.1s]
⠙ [plugin-vite] Compiling main process code
vite v4.4.9 building for development...

watching for file changes...
vite v4.4.9 building for development...

watching for file changes...

build started...

build started...
✓ 1 modules transformed.
Generated an empty chunk: "preload".
✔ [plugin-vite] Launching dev servers for renderer process code [0.1s]
✔ [plugin-vite] Launching dev servers for renderer process code [0.1s]
✔ [plugin-vite] Compiling main process code [0.3s]
[commonjs--resolver] Export 'BSON' is not defined (1:9) in ./typeorm-issue-10370/node_modules/typeorm/browser/driver/mongodb/bson.typings.js
file: ./typeorm-issue-10370/node_modules/typeorm/browser/driver/mongodb/bson.typings.js:1:9
1: export { BSON };
            ^
✔ [plugin-vite] Launching dev servers for renderer process code [0.1s]
✔ [plugin-vite] Compiling main process code [0.3s]

✨  Done in 20.37s.
```