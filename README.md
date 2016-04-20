# es6-module-boilerplate

A boilerplate for writing npm modules in ES6.

## Usage

1. Shallow-clone the repository

  ```bash
  $ git clone --depth=1 --branch=master git@github.com:angusfretwell/es6-module-boilerplate.git
  ```

2. Rename, and then change into the directory

  ```bash
  $ mv es6-module-boilerplate new-module && cd new-module
  ```

3. Remove the git repository, and the initialize a new one

  ```bash
  $ rm -rf .git && git init
  ```

4. Replace this README with the example one

  ```bash
  $ rm README.md && mv README.example.md README.md
  ```

5. Update `package.json` and install dependencies

  ```bash
  $ npm init && npm install
  ```

6. Start coding!

  ```bash
  $ $EDITOR .
  ```

## License

The MIT License (MIT)

Copyright (c) 2016 Angus Fretwell
