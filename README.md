Laravel-Identicon Package
=========================
[![Laravel Package][ico-laravel]][link-repo]
[![Latest Version on Packagist][ico-version]][link-packagist]
[![Software License][ico-license]](LICENSE.md)
[![Total Downloads][ico-downloads]][link-downloads]

> Laravel [Identicon][link-identicon] Package - Extends Identicon Library and Adds Support for Seamless Usage with Laravel. Now working with php8 & Laravel 8!

## Quick start


### Installation

```bash
$ composer require mikelucid/laravel-identicon
```

## Usage

This Package adds Laravel Support to [Identicon][link-identicon] PHP Library. It simply extends the library as well as optimized for usage with Laravel. So all the methods listed [here][link-identicon] are available and will work seamlessly.

### Example Methods

Generate and Display an identicon image:

```php
Identicon::displayImage('foo');
```

Generate and get the image data

```php
$imageData = Identicon::getImageData('bar');
```

Generate and get the base 64 image uri ready for integrate into an HTML img tag. The below example is using blade templating

```
<img src="{{ Identicon::getImageDataUri('bar') }}" alt="bar Identicon" />
```

...

And all the other remaining methods from the main library.

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) for details.

## Security

If you discover any security related issues, please email `mikelucid at gmail.com` instead of using the issue tracker.

## Credits

- [mikelucid][link-author]
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%mikelucid%2Flaravel-identicon.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%mikelucid%2Flaravel-identicon?ref=badge_large)

[ico-laravel]: https://img.shields.io/badge/Laravel-6~8-FF2D20.svg?style=flat-square&logo=laravel&labelColor=black&logoColor=white
[ico-version]: https://img.shields.io/packagist/v/irazasyed/laravel-identicon.svg?style=flat-square
[ico-license]: https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square
[ico-downloads]: https://img.shields.io/packagist/dt/mikelucid/laravel-identicon.svg?style=flat-square

[link-phpchat]: https://phpchat.co/?ref=laravel-identicon
[link-telegram]: https://t.me/PHPChatCo
[link-repo]: https://github.com/mikelucid/laravel-identicon
[link-packagist]: https://packagist.org/packages/mikelucid/laravel-identicon
[link-downloads]: https://packagist.org/packages/mikelucid/laravel-identicon
[link-author]: https://github.com/mikelucid
[link-contributors]: ../../contributors
[link-identicon]: https://github.com/yzalis/Identicon
