# uuid-doctrine-odm

[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Build Status][ico-travis]][link-travis]
[![Coverage Status][ico-scrutinizer]][link-scrutinizer]
[![Quality Score][ico-code-quality]][link-code-quality]
[![Total Downloads][ico-downloads]][link-downloads]

Allow the use of a ramsey/uuid UUID as Doctrine ODM field type.

## Install

Via Composer

``` bash
$ composer require jdr/uuid-doctrine-odm
```

## Usage

``` php
<?php

use Doctrine\ODM\MongoDB\Types\Type;

Type::registerType('ramsey_uuid', 'JDR\Uuid\Doctrine\ODM\UuidType');
Type::registerType('ramsey_uuid_binary', 'JDR\Uuid\Doctrine\ODM\UuidBinaryType');

```

## Change log

Please see [CHANGELOG](CHANGELOG.md) for more information what has changed recently.

## Testing

``` bash
$ composer test
```

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Security

If you discover any security related issues, please email dev@johanderuijter.nl instead of using the issue tracker.

## Credits

- [Johan de Ruijter][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[ico-version]: https://img.shields.io/packagist/v/jdr/uuid-doctrine-odm.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-travis]: https://img.shields.io/travis/johanderuijter/uuid-doctrine-odm/master.svg?style=flat-square
[ico-scrutinizer]: https://img.shields.io/scrutinizer/coverage/g/johanderuijter/uuid-doctrine-odm.svg?style=flat-square
[ico-code-quality]: https://img.shields.io/scrutinizer/g/johanderuijter/uuid-doctrine-odm.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/jdr/uuid-doctrine-odm.svg?style=flat-square

[link-packagist]: https://packagist.org/packages/jdr/uuid-doctrine-odm
[link-travis]: https://travis-ci.org/johanderuijter/uuid-doctrine-odm
[link-scrutinizer]: https://scrutinizer-ci.com/g/johanderuijter/uuid-doctrine-odm/code-structure
[link-code-quality]: https://scrutinizer-ci.com/g/johanderuijter/uuid-doctrine-odm
[link-downloads]: https://packagist.org/packages/jdr/uuid-doctrine-odm
[link-author]: https://github.com/johanderuijter
[link-contributors]: ../../contributors
