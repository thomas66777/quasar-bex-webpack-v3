
quasar dev -m bex

```sh
Uncaught EvalError: Refused to evaluate a string as JavaScript because 'unsafe-eval' is not an allowed source of script in the following Content Security Policy directive: "script-src 'self'".

    at ./node_modules/webpack-dev-server/client/index.js?protocol=ws%3A&hostname=0.0.0.0&port=8080&pathname=%2Fws&logging=warn&overlay=%7B%22errors%22%3Atrue%2C%22warnings%22%3Afalse%7D&reconnect=10&hot=true&live-reload=true (vendor.js:270:1)
    at __webpack_require__ (app.js:204:32)
    at app.js:1390:63
    at __webpack_require__.O (app.js:244:23)
    at app.js:1393:53
    at app.js:1395:12
```