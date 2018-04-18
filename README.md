## Run Unit Tests

```
npm test
// Or the watching mode
npm run test1
```

## Debug

1. Write a debug file at `test/debugs/your.debug.js`
2. Run the debug command

  ```
  babel-node --harmony --inspect-brk test/debugs/your.debug.js
  ```
3. Open the Chrome inspector interface

  ```
  chrome://inspect/
  ```

  You will see the files listed for inspcecting.

4. Add the `fs` folder to the chrome-devtools's workspace

## Docs

The documents are generated by jsdoc([jsdoc-to-markdown](https://www.npmjs.com/package/jsdoc-to-markdown)) along with gitbook([gitbook-cli](https://www.npmjs.com/package/gitbook-cli)) following this [guide](https://medium.com/@kevinast/integrate-gitbook-jsdoc-974be8df6fb3).