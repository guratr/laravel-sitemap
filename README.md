# **Victorbuild Sitemap package**

[![PHP tests](https://github.com/victorbuild/laravel-sitemap/workflows/PHP%20tests/badge.svg?branch=master)](https://github.com//victorbuild/laravel-sitemap/actions?query=workflow%3A%22PHP+tests%22) [![Maintainability](https://api.codeclimate.com/v1/badges/c7b8c0079addb1217836/maintainability)](https://codeclimate.com/github/victorbuild/laravel-sitemap/maintainability) [![Test Coverage](https://api.codeclimate.com/v1/badges/c7b8c0079addb1217836/test_coverage)](https://codeclimate.com/github/victorbuild/laravel-sitemap/test_coverage) [![Style Status](https://github.styleci.io/repos/10392044/shield?style=normal&branch=master)](https://github.styleci.io/repos/10392044) [![Latest Stable Version](https://poser.pugx.org/victorbuild/sitemap/v/stable)](https://packagist.org/packages/victorbuild/sitemap) [![Total Downloads](https://poser.pugx.org/victorbuild/sitemap/downloads)](https://packagist.org/packages/victorbuild/sitemap)

*Sitemap generator for Laravel9.*

## Notes

- Dev Branches are for development and are **UNSTABLE** (*use on your own risk*)!

## Installation

Run the following command and provide the latest stable version (e.g v8.\*) :

```bash
composer require victorbuild/sitemap
```

*or add the following to your `composer.json` file :*

#### For Laravel 9
```json
"victorbuild/sitemap": "9.*"
```
(development branch)
```json
"victorbuild/sitemap": "9.x-dev"
```

*Publish needed assets (styles, views, config files) :*

```bash
php artisan vendor:publish --provider="Victorbuild\Sitemap\SitemapServiceProvider"
```
**Note:** *Composer won't update them after `composer update`, you'll need to do it manually!*

## Examples

- [How to generate dynamic sitemap (with optional caching)](https://github.com/victorbuild/laravel-sitemap/wiki/Dynamic-sitemap)

- [How to generate BIG sitemaps (with more than 1M items)](https://github.com/victorbuild/laravel-sitemap/wiki/Sitemap-index)

- [How to generate sitemap to a file](https://github.com/victorbuild/laravel-sitemap/wiki/Generate-sitemap)

- [How to use multiple sitemaps with sitemap index](https://github.com/victorbuild/laravel-sitemap/wiki/Generate-BIG-sitemaps)

and more in the [Wiki](https://github.com/victorbuild/laravel-sitemap/wiki).

## Contribution guidelines

Before submiting new merge request or creating new issue, please read [contribution guidelines](https://gitlab.com/victorbuild/Sitemap/blob/master/CONTRIBUTING.md).

## License

This package is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
