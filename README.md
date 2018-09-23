> This package has been moved to the [pnpm](https://github.com/pnpm/pnpm) multi-package repository.

# @pnpm/outdated

> Check for outdated packages

<!--@shields('npm', 'travis')-->
[![npm version](https://img.shields.io/npm/v/@pnpm/outdated.svg)](https://www.npmjs.com/package/@pnpm/outdated) [![Build Status](https://img.shields.io/travis/pnpm/outdated/master.svg)](https://travis-ci.org/pnpm/outdated)
<!--/@-->

## Installation

```sh
npm i -S @pnpm/outdated
```

## API

### default: `outdated(path, opts): Promise<OutdatedPackage[]>`

Returns an array of outdated packages.

### Arguments

- `path` - _String_ - path to the project

### `forPackages(packages, path, opts): Promise<OutdatedPackage[]>`

Returns an array of outdated packages for the specified packages.

### Arguments

- `path` - _String_ - path to the project

## License

[MIT](LICENSE) © [Zoltan Kochan](https://www.kochan.io/)
