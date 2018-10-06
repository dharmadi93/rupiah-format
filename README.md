# rupiah-format

## Synopsis

This library converts standard numbers format into Indonesian currency format (Rupiah)

## Installation

```npm install```

## Code Example

```
//require library
const convertRupiah = require('rupiah-format')

//convert number
let number = 1000000
let rupiah = convertRupiah.convert(number)

console.log(rupiah)

```

## Tests

```
node test
```

## License

MIT