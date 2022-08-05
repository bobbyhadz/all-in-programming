# All in programming

This is a repository for my book
[All in Programming](https://bobbyhadz.com/blog/all-in-programming).

Check out the instructions in the
[CONTRIBUTING.md](https://github.com/bobbyhadz/all-in-programming/blob/main/CONTRIBUTING.md)
file for how to contribute.

Make sure to pick unique filenames when contributing. Each contribution should
consist of a `sum` function and a test for the function.

```javascript
// src/sum15And15.js

export function sum15And15() {
  return 15 + 15;
}
```

And here is the test for the function.

```javascript
// test/sum15And15.test.js

import {sum15And15} from '../src/sum15And15';

it('returns 30 when adding 15 and 15', () => {
  expect(sum15And15()).toBe(30);
});
```
