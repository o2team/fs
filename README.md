# 📦🚀 @aotu/fs

Useful file system utilities.

<!--- Badges for CI Builds --->
[![Build Status](https://travis-ci.org/mamboer/fs.svg?branch=master)](https://travis-ci.org/mamboer/fs)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/bc05341458d04003b781d01c3e1feac8)](https://www.codacy.com/app/mamboer/fs?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=mamboer/fs&amp;utm_campaign=Badge_Grade)
[![Coverage Status](https://coveralls.io/repos/github/mamboer/fs/badge.svg?branch=master)](https://coveralls.io/github/mamboer/fs?branch=master)
[![NPM Version Badge](https://img.shields.io/npm/v/@aotu/fs/latest.svg)](https://www.npmjs.com/package/@aotu/fs)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)


✅ An **experimental** project applying several cool stuffs, a boilerplate for writing new NPM packages.

✓ Auto-release with [semantic-release](https://github.com/semantic-release/semantic-release)

✓ Fast Unit Tests with [ava](https://www.npmjs.com/package/ava)

✓ Coverage with [nyc](https://www.npmjs.com/package/nyc)

✓ Automated Code reviews with [codacy](https://www.codacy.com/)

✓ Elegant documents via [jsdoc-to-markdown](https://www.npmjs.com/package/jsdoc-to-markdown) along with [gitbook](https://www.npmjs.com/package/gitbook-cli)

✓ Scoped NPM package

✓ Publish gh-pages automatically via [travis-ci](https://travis-ci.org/)

✓ Semantic git commits via [semantic-git-commit-cli](https://www.npmjs.com/package/semantic-git-commit-cli)

## Unit Tests

```
npm test
// Or the watching mode
npm run test1
```

## Debug

1. Write a debug file at `test/debugs/your.debug.js`
2. Run the debug command

  ```
  node --inspect-brk test/debugs/your.debug.js
  ```
3. Open the Chrome inspector interface

  ```
  chrome://inspect/
  ```

  You will see the files listed for inspcecting.

4. Add the `fs` folder to the chrome-devtools's workspace

## Docs

The documents are generated by jsdoc([jsdoc-to-markdown](https://www.npmjs.com/package/jsdoc-to-markdown)) along with gitbook([gitbook-cli](https://www.npmjs.com/package/gitbook-cli)) following this [guide](https://medium.com/@kevinast/integrate-gitbook-jsdoc-974be8df6fb3).

1. Initial build

  ```shell
  npm run docs
  ```

2. Incremental build

  ```shell
  npm run docs:build
  ```

3. Watching Mode

  ```shell
  npm run docs:serve
  ```

4. Clean the generated docs

  ```shell
  npm run docs:clean
  ```

## Release

The module will be released automatically by [semantic-release](https://www.npmjs.com/package/semantic-release-cli)
