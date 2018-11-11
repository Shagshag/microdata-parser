# microdata-parser

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

This package aims to implement [W3C Microdata Specification](https://www.w3.org/TR/microdata/).

**microdata-parser** extracts microdata from documents.

## Installation

Via Composer

``` bash
$ composer require yusufkandemir/microdata-parser
```

## Usage

``` php
$parser = new YusufKandemir\MicrodataParser();
$microdata = $parser->extractMicrodata();
```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information on what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](.github/CONTRIBUTING.md) for details.

## Credits

- [Yusuf Kandemir][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/yusufkandemir/microdata-parser.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/yusufkandemir/microdata-parser/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/yusufkandemir/microdata-parser.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/yusufkandemir/microdata-parser.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/yusufkandemir/microdata-parser.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/yusufkandemir/microdata-parser
[link-travis]: https://travis-ci.org/yusufkandemir/microdata-parser
[link-scrutinizer]: https://scrutinizer-ci.com/g/yusufkandemir/microdata-parser/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/yusufkandemir/microdata-parser
[link-downloads]: https://packagist.org/packages/yusufkandemir/microdata-parser
[link-author]: https://github.com/yusufkandemir
[link-contributors]: ../../contributors