[![Tests](https://github.com/ramxis/SafeSolidityTest/actions/workflows/test.yml/badge.svg)](https://github.com/ramxis/SafeSolidityTest/actions/workflows/test.yml)
[![Lint](https://github.com/ramxis/SafeSolidityTest/actions/workflows/lint.yml/badge.svg)](https://github.com/ramxis/SafeSolidityTest/actions/workflows/lint.yml)

# SampleSafeModule

## TokenWithdrawalModule

This contract defines a TokenWithdrawalModule contract that implements allows any account not related to safe to withdraw X amounts of UnicornTokens from the safe given that they provide valid signature from one of the owners of the safe

# TODO

Try running some of the following tasks:

## Linting

`npm run linter`

## Tests

Tests can be run using:
`npm test`

## code coverage

Coverage report can be generated by running:
`npm run coverage`

```shell
npm run compile
npm run test
npm run linter
npm run coverage
```
