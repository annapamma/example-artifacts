# circlecidemo-fizzbuzz

An NPM package for demonstrating basic CircleCI concepts, including:
- [pipelines](https://circleci.com/docs/2.0/pipelines/)
- [workflows](https://circleci.com/docs/2.0/jobs-steps/)
- [jobs](https://circleci.com/docs/2.0/pipelines/#jobs-tests-artifacts)

The CircleCI config includes jobs for a simple test and deploy/publish cycle.

## Usage

Installation
```sh
yarn add circlecidemo-fizzbuzz
```

Usage
```js
const fizzbuzz = require('circledemo-fizzbuzz')

fizzbuzz(6)
```

Output:
```
1
2
Fizz
4
Buzz
```