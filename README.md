[![Packagist](https://img.shields.io/packagist/dt/creaminternet/theme-blank-sass.svg)](https://packagist.org/packages/creaminternet/theme-blank-sass)
# SASS Blank theme for Magento 2
The official fork of the SASS Blank theme from Snowdog.

SASS based version of Magento 2 Blank theme, which aims to be as close to the core code as possible.

## Installation
1. Install via composer
```
composer require creaminternet/theme-blank-sass
```
2. Enable module
```
bin/magento setup:upgrade
```   
3. Compile SASS files using [Frontools](https://github.com/creaminternet/magento2-frontools)

## Compatibility
* Magento 2.4: v1.5.0 or later
* Magento 2.3: v1.2.0 or later
* Magento 2.2: v1.0.0 or later
* Magento 2.1: v0.11.0 or older
* Magento 2.0: v0.6.0 or older

## Bug reports and contribution rules
- Before reporting an issue, check if you can reproduce it on the clean Magento instance with LESS version of the Blank theme. If that's true, submit issue to the Magento 2 repository
- If you know how to fix an issue, which is reproducible in Magento core, submit PR to the core product first, then here, with a link to PR in Magento 2 repository
- If issue is related only to the SASS port, feel free to submit issue or PR
