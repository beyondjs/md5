# @beyond-js/md5

A fast and efficient MD5 hash implementation for JavaScript, compatible with both Node.js and browser environments.

## Installation

```bash
npm install @beyond-js/md5
```

## Usage

```javascript
const md5 = require('@beyond-js/md5');

const hash = md5('Hello, World!');
console.log(hash); // Outputs: 65a8e27d8879283831b664bd8b7f0ad4
```

## API

The module exports a single function:

```javascript
function md5(str: string): string
```

-   `str`: The input string to be hashed.
-   Returns: A lowercase string representing the MD5 hash of the input.

## Features

-   Fast and efficient MD5 implementation
-   Works with strings as input
-   Returns lowercase MD5 hash
-   No external dependencies
-   Compatible with Node.js and browser environments

## Implementation Details

This MD5 implementation is based on the RSA Data Security, Inc. MD5 Message-Digest Algorithm. It includes optimizations
for performance, such as:

-   Pre-computed lookup tables
-   Bitwise operations for speed
-   Efficient word array conversion

## License

MIT © [[BeyondJS](https://beyondjs.com)]
