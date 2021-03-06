# Accounting

[![Latest Stable Version](https://poser.pugx.org/vjik/accounting/v/stable.png)](https://packagist.org/packages/vjik/accounting)
[![Total Downloads](https://poser.pugx.org/vjik/accounting/downloads.png)](https://packagist.org/packages/vjik/accounting)
[![Build status](https://github.com/vjik/accounting/workflows/build/badge.svg)](https://github.com/vjik/accounting/actions?query=workflow%3Abuild)
[![Mutation testing badge](https://img.shields.io/endpoint?style=flat&url=https%3A%2F%2Fbadge-api.stryker-mutator.io%2Fgithub.com%2Fvjik%2Faccounting%2Fmaster)](https://dashboard.stryker-mutator.io/reports/github.com/vjik/accounting/master)
[![static analysis](https://github.com/vjik/accounting/workflows/static%20analysis/badge.svg)](https://github.com/vjik/accounting/actions?query=workflow%3A%22static+analysis%22)

The package provide accounting system.

## Installation

The package could be installed with [composer](https://getcomposer.org/download/):

```shell
composer require vjik/accounting --prefer-dist
```

## General usage

## Testing

### Unit testing

The package is tested with [PHPUnit](https://phpunit.de/). To run tests:

```shell
./vendor/bin/phpunit
```

### Mutation testing

The package tests are checked with [Infection](https://infection.github.io/) mutation framework with
[Infection Static Analysis Plugin](https://github.com/Roave/infection-static-analysis-plugin). To run it:

```shell
./vendor/bin/roave-infection-static-analysis-plugin
```

### Static analysis

The code is statically analyzed with [Psalm](https://psalm.dev/). To run static analysis:

```shell
./vendor/bin/psalm
```

## License

The Accounting is free software. It is released under the terms of the BSD License.
Please see [`LICENSE`](./LICENSE.md) for more information.
