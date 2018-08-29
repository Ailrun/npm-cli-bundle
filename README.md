# @ailrun/cli-bundle

## How to Install

``` shell
npm i -D @ailrun/cli-bundle
```

## Package Included
- `npm-run-all`
  CLI for run multiple npm scripts in single npm script.
- `rimraf`
  CLI for running `rm -rf` on specific directory. This package is useful for writing a script for cleaning.
- `cross-env`
  CLI for adding environment variable temporarily for current command. For example, you want to use a env variable `BUILD_STAGE` of `'COMPRESSING'`, only for `npm pack`, you can use `cross-env BUILD_STAGE=COMPRESSING npm pack`
