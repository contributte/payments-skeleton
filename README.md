![](https://heatbadger.now.sh/github/readme/contributte/payments-skeleton/)

<p align=center>
  <a href="https://github.com/contributte/payments-skeleton/actions"><img src="https://badgen.net/github/checks/contributte/payments-skeleton/master"></a>
  <a href="https://codecov.io/gh/contributte/payments-skeleton"><img src="https://badgen.net/codecov/c/github/contributte/payments-skeleton"></a>
  <a href="https://packagist.org/packages/contributte/payments-skeleton"><img src="https://badgen.net/packagist/dm/contributte/payments-skeleton"></a>
  <a href="https://packagist.org/packages/contributte/payments-skeleton"><img src="https://badgen.net/packagist/v/contributte/payments-skeleton"></a>
</p>
<p align=center>
  <a href="https://packagist.org/packages/contributte/payments-skeleton"><img src="https://badgen.net/packagist/php/contributte/payments-skeleton"></a>
  <a href="https://github.com/contributte/payments-skeleton"><img src="https://badgen.net/github/license/contributte/payments-skeleton"></a>
  <a href="https://bit.ly/ctteg"><img src="https://badgen.net/badge/support/gitter/cyan"></a>
  <a href="https://bit.ly/cttfo"><img src="https://badgen.net/badge/support/forum/yellow"></a>
  <a href="https://contributte.org/partners.html"><img src="https://badgen.net/badge/sponsor/donations/F96854"></a>
</p>

<p align=center>
Website 🚀 <a href="https://contributte.org">contributte.org</a> | Contact 👨🏻‍💻 <a href="https://f3l1x.io">f3l1x.io</a> | Twitter 🐦 <a href="https://twitter.com/contributte">@contributte</a>
</p>

<p align=center>
    <img src="https://api.microlink.io?url=https%3A%2F%2Fexamples.contributte.org%2Fpayments-skeleton%2F&overlay.browser=light&screenshot=true&meta=false&embed=screenshot.url"></img>
</p>

-----

This project is a small [Nette](https://nette.org) example for integrating [contributte/thepay](https://contributte.org/packages/contributte/thepay.html).

## Demo

https://examples.contributte.org/payments-skeleton/

## Installation

To install latest version of `contributte/payments-skeleton` use [Composer](https://getcomposer.org).

### Requirements

- PHP 8.4+
- PHP `ext-bcmath`

```bash
composer create-project -s dev contributte/payments-skeleton acme
cd acme
make project
```

### Composer packages

## Startup

```bash
make dev
```

Open [http://localhost:8000](http://localhost:8000). The default route is `Homepage:default`.

## ThePay configuration

The ThePay DI extension is registered in `config/thepay.neon`, which is included from `config/config.neon`. Configure provider credentials and payment settings in your application-specific configuration; do not commit production credentials to this skeleton.

## Commands

```bash
make qa       # coding standard and static analysis
make cs       # coding standard only
make csf      # fix coding style
make phpstan  # run static analysis
make clean    # remove temporary files and logs
```

## Development

See [how to contribute](https://contributte.org/contributing.html) to this package.

This package is currently maintaining by these authors.

<a href="https://github.com/f3l1x">
    <img width="80" height="80" src="https://avatars2.githubusercontent.com/u/538058?v=3&s=80">
</a>
<a href="https://github.com/petrparolek">
  <img width="80" height="80" src="https://avatars2.githubusercontent.com/u/6066243?v=3&s=80">
</a>

-----

Consider to [support](https://contributte.org/partners.html) **contributte** development team. Also thank you for using this project.
