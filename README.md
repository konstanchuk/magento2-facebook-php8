# magento2-facebook-php8
PHP8 compatibility patches for Facebook Magento 2 Extension [https://github.com/facebookincubator/facebook-for-magento2](https://github.com/facebookincubator/facebook-for-magento2).

You need to install [https://github.com/cweagans/composer-patches](https://github.com/cweagans/composer-patches) and add the following lines to composer.json.

```php
    "extra": {
        "magento-force": "override",
        "composer-exit-on-patch-failure": true,
        "patches": {
            "facebook/php-business-sdk": {
                "facebook-php8fix-1": "patches/composer/facebook-php8fix/1.diff",
                "facebook-php8fix-2": "patches/composer/facebook-php8fix/2.diff",
                "facebook-php8fix-3": "patches/composer/facebook-php8fix/3.diff",
                "facebook-php8fix-4": "patches/composer/facebook-php8fix/4.diff",
                "facebook-php8fix-5": "patches/composer/facebook-php8fix/5.diff",
                "facebook-php8fix-6": "patches/composer/facebook-php8fix/6.diff",
                "facebook-php8fix-7": "patches/composer/facebook-php8fix/7.diff",
                "facebook-php8fix-8": "patches/composer/facebook-php8fix/8.diff",
                "facebook-php8fix-9": "patches/composer/facebook-php8fix/9.diff"
            }
        }
    }
```

Don't forget to copy the patches to your project.

--
