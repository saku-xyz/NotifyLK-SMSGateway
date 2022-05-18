# NotifyLk
Send SMS with Notify.lk

- API version: v1
- Package version: 1.0
- Build package: class io.swagger.codegen.languages.PhpClientCodegen

## Requirements

PHP 5.4.0 and later

## Installation & Usage
### Composer

To install the bindings via [Composer](http://getcomposer.org/), add the following to `composer.json`:

```
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/notifylk/notify-php.git"
    }
  ],
  "require": {
    "notifylk/notify-php": "*@dev"
  }
}
```

Then run `composer install`

### Manual Installation

Download the files and include `autoload.php`:

```php
    require_once('/path/to/NotifyLk/autoload.php');
```

## Tests

To run the unit tests:

```
composer install
./vendor/bin/phpunit
```

## Documentation for API Endpoints

All URIs are relative to *https://app.notify.lk/api/v1*

Class | Method | HTTP request | Description
------------ | ------------- | ------------- | -------------
*SmsApi* | [**sendSMS**](docs/Api/SmsApi.md#sendsms) | **POST** /send | Sending SMS to a number from specified sender ID



