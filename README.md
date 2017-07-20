# Introduction

[![Greenkeeper badge](https://badges.greenkeeper.io/Frederick-S/irregular-verbs-de.svg)](https://greenkeeper.io/)
Conjugation of irregular verbs in German.
# Usage
```js
var verbs = require('irregular-verbs-de');
var go = verbs['gehen'];
console.log(`${go.infinitive}`, `${go.pastTense}`, `${go.presentPerfect}`);
```
Output:
```sh
gehen, ging, gegangen
```
# License
MIT.
