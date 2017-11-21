# Respect\Validation

[![Build Status](https://img.shields.io/travis/Respect/Validation/master.svg?style=flat-square)](http://travis-ci.org/Respect/Validation)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/Respect/Validation/master.svg?style=flat-square)](https://scrutinizer-ci.com/g/Respect/Validation/?branch=master)
[![Code Coverage](https://img.shields.io/scrutinizer/coverage/g/Respect/Validation/master.svg?style=flat-square)](https://scrutinizer-ci.com/g/Respect/Validation/?branch=master)
[![最新稳定版本](https://img.shields.io/packagist/v/respect/validation.svg?style=flat-square)](https://packagist.org/packages/respect/validation)
[![总下载数量](https://img.shields.io/packagist/dt/respect/validation.svg?style=flat-square)](https://packagist.org/packages/respect/validation)
[![License](https://img.shields.io/packagist/l/respect/validation.svg?style=flat-square)](https://packagist.org/packages/respect/validation)

[The most awesome validation engine ever created for PHP.](http://bit.ly/1a1oeQv)

- 使复杂的规则变得简单： `v::numericVal()->positive()->between(1, 255)->validate($input)`.
- [先进的粒度控制报告](docs/README.md#validation-methods).
- 超过100（完全测试）个验证器.
- [A concrete API](docs/CONCRETE_API.md) for non fluent usage.
- 适用于 PHP 5.6+

## 目录

- 安装

安装包在 [Packagist](http://packagist.org/packages/respect/validation),
可以使用 [Composer](http://getcomposer.org).

```shell
composer require respect/validation
```

- [功能向导](docs/README.md)
- [验证器](docs/VALIDATORS.md)
- [版本历史](CHANGELOG.md)
- [贡献](CONTRIBUTING.md)
- [版权](LICENSE.md)
