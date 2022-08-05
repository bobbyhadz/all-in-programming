## Contributing

Hello folks 👋

Follow the step by step instructions to contribute to the repository.

## Pull Request Guidelines

1. Fork the repository.
2. Git clone the fork with the SSH URL

```bash
git clone git@github.com:bobbyhadz/aip.git
```

3. Change to the directory of the repository

```bash
cd aip
```

4. Pull from the original repository

```bash
git pull git@github.com:bobbyhadz/aip.git -v
```

5. Create a new branch

```bash
git checkout -b feat/add_5_and_5
```

6. Install the dependencies

```bash
npm install
```

7. Run the tests before making any changes

```bash
npm run test
```

Alternatively, you can run the tests in watch mode to have them re-run every
time you make a change.

```bash
npm run test:watch
```

8. Create a `sum` function that adds 2 numbers in the `src` directory, e.g.
   under `src/sum5And5`. You can use any of the other `sum` functions as a
   template.

```javascript
// src/sum5And5.js

export function sum5And5() {
  return 5 + 5;
}
```

9. Add a test for the function in the `test` directory, e.g. under
   `test/sum5And5.test.js`.

```javascript
// test/sum5And5.test.js

import {sum5And5} from '../src/sum5And5';

it('returns 10 when adding 5 and 5', () => {
  expect(sum5And5()).toBe(10);
});
```

10. After you finish, re-run the tests to make sure all tests pass with the
    changes you've made.

```bash
npm run test
```

11. Pull in changes from the upstream (the original remote repository) to stay
    up to date and avoid merge conflicts

```bash
git pull git@github.com:bobbyhadz/aip.git -v
```

12. Add and commit the changes you made

```bash
git add .

git commit -m 'add sum5And5 function'
```

13. Run the `git push` command and look at the error message.

```bash
git push
```

The error message will tell you what command you need to run to push the current
branch and set the remote as upstream.

14. Run the command from the error message. You only have to run this command
    the first time you push to the remote branch.

```bash
git push --set-upstream origin feat/add_5_and_5
```

15. Push the changes to your remote.

```bash
git push -v
```

16. Open your Github fork and make a Pull request to the `main` branch of the
    original repository.

17. I will merge your pull request as soon as possible! 🎊
