# nabu-3 JSON Utils library
[![GitHub](https://img.shields.io/github/license/nabu-3/json-utils.svg)](https://opensource.org/licenses/Apache-2.0)
[![Build Status](https://travis-ci.org/nabu-3/json-utils.svg?branch=master)](https://travis-ci.org/nabu-3/json-utils)
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=nabu-3_json-utils&metric=alert_status)](https://sonarcloud.io/dashboard?id=nabu-3_json-utils)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=nabu-3_json-utils&metric=sqale_rating)](https://sonarcloud.io/dashboard?id=nabu-3_json-utils)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=nabu-3_json-utils&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=nabu-3_json-utils)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=nabu-3_json-utils&metric=security_rating)](https://sonarcloud.io/dashboard?id=nabu-3_json-utils)

This is a library to extend minimal-class nabu-3 package with new features to support JSON files and data fields containing JSON data in string format. You can use this library at your convenience and stay out of the nabu-3 core framework to allow other nabu-3 projects to live independently and to be used outside this framework.

Package is provided under [Apache 2.0 license](https://github.com/nabu-3/json-utils/blob/master/LICENSE) and you can use it under those terms.
## Install package
The package is deployed using composer and packagist and you can install it with this command:
```sh
composer require nabu-3/json-utils
```
## How to use in your project
To use this package, you only need to include the autoload file of vendor folder:
```php
require_once 'vendor/autoload.php'
```
