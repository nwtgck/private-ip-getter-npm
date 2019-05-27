# private-ip-getter

Private IP Getter for Web Browser

## Installation

```bash
npm i -S git+https://github.com/nwtgck/private-ip-getter-web.git#master
```

## Usage

```js
import {getPrivateIP} from 'private-ip-getter';

(async () => {
  const ip = await getPrivateIP();
  console.log('Private IP Address:', ip);
})();
```
