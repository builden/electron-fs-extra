# electron-fs-extra
use fs-extra at electron render process

## how to use
the same with fs-extra
```js
import fs from 'electron-fs-extra';

async readFile(filePath) {
  return await fs.readFile(filePath)
}

readFile(filePath);
```

## Note
must install [fs-extra](https://github.com/jprichardson/node-fs-extra) first at project
```bash
$ yarn add fs-extra

# or
$ npm install fs-extra -S
```