## Slim Framework v2

Slim is a PHP micro framework that helps you quickly write simple yet powerful web applications and APIs. Learn more at these links:

- [Website](http://www.slimframework.com/)
- [Documentation](http://docs.slimframework.com/)
- [Support Forum](http://help.slimframework.com/)
- [Twitter](https://twitter.com/slimphp)

This repository contains documentation for the legacy 2.x branch.

## Install

Via [Composer](https://getcomposer.org/)

```
$ composer require slim/slim:~2.0
```

Requires PHP 5.3.0 or newer.

### Usage

```
$app = new \Slim\Slim();
$app->get('/hello/:name', function ($name) {
    echo "Hello, " . $name;
});
$app->run();
```

### Testing

```
phpunit
```

### Contributing

Please see [CONTRIBUTING](https://github.com/slimphp/Slim/blob/master/CONTRIBUTING.md) for details.

### Security

If you discover any security related issues, please email security@slimframework.com instead of using the issue tracker.

### Credits

- [Josh Lockhart](https://github.com/codeguy)
- [Andrew Smith](https://github.com/silentworks)
- [Gabriel Manricks](https://github.com/gmanricks)
- [All Contributors](https://github.com/slimphp/Slim/graphs/contributors)

### License

The MIT License (MIT). Please see [License File](https://github.com/slimphp/Slim/blob/master/LICENSE.md) for more information.
