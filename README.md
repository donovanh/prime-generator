# Prime Generator

A simple function that generates prime numbers between a given range. 

## Usage

In a web application, import and use the function like so:

```js
import { generate } from './primes'

generate(1, 100) // Returns array of primes between 1 and 100
```

In Node / server-side JS:

```js
const primes = require('./js/cjs')

primes.generate(1, 100)
```

In the browser:

```html
<script src="./js/browser/primes.js"></script>

<script>
  const result = primes.generate(1, 100)
  // Result contains array of prime numbers
</script>
```

## Performance considerations

This is just a simple demo project and generating large prime numbers is not well suited to this JavaScript implementation. In general though, calculating primes within 1 and 200,000 should perform reasonably well. It gets exponentially slower for higher numbers.

## MIT License

Copyright 2021 Donovan Hutchinson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

