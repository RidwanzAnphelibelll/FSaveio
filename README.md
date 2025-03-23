# FSaveio

A Node.js library for downloading media from various social media platforms.

## Installation

```sh
npm i fsaveio
```

## Example Usage

### TikTok

```js
const { tiktok } = require('fsaveio');

const url = 'https://vm.tiktok.com/ZSr1nuuV5/';

async function main() {
  try {
    const results = await tiktok(url);
    console.log(results);
  } catch (error) {
    console.error('Error:', error.message);
  }
}

main();
```

### Facebook

```js
const { facebook } = require('fsaveio');

const url = 'https://www.facebook.com/share/r/1PtdoNL2Gy/';

async function main() {
  try {
    const results = await facebook(url);
    console.log(results);
  } catch (error) {
    console.error('Error:', error.message);
  }
}

main();
```

### Instagram

```js
const { instagram } = require('fsaveio');

const url = 'https://www.instagram.com/reel/DHQFNfnR1rc/?igsh=YzljYTk1ODg3Zg==';

async function main() {
  try {
    const results = await instagram(url);
    console.log(results);
  } catch (error) {
    console.error('Error:', error.message);
  }
}

main();
```

## Contributions and Issue Reporting

If you encounter any issues or would like to contribute to the development of this library, please visit our [GitHub repository](https://github.com/RidwanzAnphelibelll/FSaveio) page.

## License

 fsaveio is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please refer to the LICENSE file for more information.
