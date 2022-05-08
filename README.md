# Gen-RandInt-Array (For Server Side)

## Contents

- [Gen-RandInt-Array (For Server Side)](#gen-randint-array-for-server-side)
  - [Contents](#contents)
  - [Description](#description)
  - [Usage](#usage)
    - [Server-side Only](#server-side-only)
  - [Requirements](#requirements)
  - [Contributing](#contributing)
  - [License](#license)

## Description

Gen-RandInt-Array is a helper function to help you generate an array of a specified size with random integers, setting the range of possible values using the from and to arguments.

Compatible with both client-side and server-side environments.

## Usage

### Server-side Only

Install the **Gen-RandInt-Array** package with [NPM](https://www.npmjs.org/):

```sh
npm install gen-randint-array-cjs
```

Now when that is done, in your application code, using the `require()` import the `genRandIntArray()` method and assign the return value to a variable:

```js
var genRandIntArray = require('gen-randint-array-cjs');

const array = genRandIntArray(10, 10, 5); // Returns an array of 10 random values ranging from 10 to 5
```

## Requirements

The Gen-RandInt-Array helper function has zero dependencies.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

The Gen-RandInt-Array Project is released under the [Apache License](http://www.apache.org/licenses/).
