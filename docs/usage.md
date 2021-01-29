# Usage


## Run
> How to start the app locally

- Yarn
    ```sh
    $ yarn start
    ```
- NPM
    ```sh
    $ npm start
    ```

Open in the browser:

- [localhost:3000/react-quickstart](http://localhost:3000/react-quickstart)

The subpath is derived from a value in [package.json](/package.json) and allows the site to work properly on a subpath on GitHub Pages.

If you make changes in the app, the browser will update to show the latest page.

See more commands covered in the CLI-generated [Bootstrapped Readme](bootstrapped-readme.md).


## Run tests

Run tests in watch mode - only files that are changed are tested and the command stays running ready to rerun tests.

- Yarn
    ```sh
    $ yarn test
    ```
- NPM
    ```sh
    $ npm test
    ```

Sample output:

```
 PASS  src/App.test.js
  ✓ renders Hello world (36ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        4.116s
Ran all test suites related to changed files.
```
