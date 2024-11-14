# linebreakr

Easy-to-use regex functions to format line breaks as Carriage Return Line Feed *CR LF* (Windows), Line Feed *LF* (Unix) and Carriage Return *CR* (Mac OS <= 9)

## Installation

```sh
npm i linebreakr
```

## Usage

A few examples of useful commands and/or tasks.

```javascript
import { crlf, lf, cr } from 'linebreakr';

let str = '\rHello\nWorld\r\n';

console.log(crlf(str)); // --> '\r\nHello\r\nWorld\r\n'
console.log(lf(str)); // --> '\nHello\nWorld\n'
console.log(cr(str)); // --> '\rHello\rWorld\r'
```

## Contributing

Contributions welcome.

## License

The MIT License (MIT) 2024 - clhilgert. Please refer to LICENSE for more details.