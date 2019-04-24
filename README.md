# primeChecker
**Simple prime checker (JS&amp;WASM performance comparison)**

Run:
```
emcc lib/prime.c -s WASM=1 -s EXPORTED_FUNCTIONS="['_isPrime','_checkPrimes']" -o public/prime.js

node server.js
```

Finally, go to localhost:2222 in your browser.
