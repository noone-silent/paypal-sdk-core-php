# Backup for PayPal PHP SDKs


## For composer.json add

```php
  "repositories": [
    {
      "type": "package",
      "package": {
        "name": "paypal/merchant-sdk-php",
        "version": "v3.12.0",
        "dist": {
          "type": "zip",
          "url": "https://raw.githubusercontent.com/noone-silent/paypal-sdk-core-php/main/paypal-merchant-sdk-php.zip"
        },
        "require": {
          "ext-curl": "*",
          "paypal/sdk-core-php": "3.*",
          "php": ">=5.3.0"
        },
        "type": "library",
        "autoload": {
          "psr-0": {
            "PayPal\\Service": "lib/",
            "PayPal\\PayPalAPI": "lib/",
            "PayPal\\EBLBaseComponents": "lib/",
            "PayPal\\EnhancedDataTypes": "lib/",
            "PayPal\\CoreComponentTypes": "lib/"
          }
        },
        "license": [
          "Apache-2.0"
        ]
      }
    },
    {
      "type": "package",
      "package": {
        "name": "paypal/sdk-core-php",
        "version": "3.4.0",
        "dist": {
          "type": "zip",
          "url": "https://raw.githubusercontent.com/noone-silent/paypal-sdk-core-php/main/paypal-sdk-core-php.zip"
        },
        "require": {
          "ext-curl": "*",
          "php": ">=5.3.0"
        },
        "require-dev": {
          "phpunit/phpunit": "3.7.*"
        },
        "type": "library",
        "autoload": {
          "psr-0": {
            "PayPal": "lib/"
          }
        },
        "license": [
          "Apache-2.0"
        ]
      }
    },
    {
      "type": "package",
      "package": {
        "name": "paypal/permissions-sdk-php",
        "version": "v3.9.1",
        "dist": {
          "type": "zip",
          "url": "https://raw.githubusercontent.com/noone-silent/paypal-sdk-core-php/main/paypal-permissions-sdk-php.zip"
        },
        "require": {
          "ext-curl": "*",
          "paypal/sdk-core-php": "3.*",
          "php": ">=5.3.0"
        },
        "type": "library",
        "autoload": {
          "psr-0": {
            "PayPal\\Types": "lib/",
            "PayPal\\Service": "lib/"
          }
        },
        "license": [
          "Apache2"
        ]
      }
    }
  ]
```
