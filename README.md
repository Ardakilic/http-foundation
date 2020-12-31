HttpFoundation Component That includes SameSite Flags With PHP>=7.3
========================
This fork is to ensure Laravel 4.2 applications that work with PHP7.3 to include SameSite=None flags.

The discussion is based on here:

https://github.com/laravel/framework/issues/30832

To include this into your Laravel 4.2 project, simply update your `composer.json` like this:

```json
{
    "repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/Ardakilic/http-foundation"
        }
    ],
    "require": {
        "symfony/http-foundation": "dev-2.7-samesite"
    }
}
```


Below is the original ReadMe:

--------


HttpFoundation Component
========================

The HttpFoundation component defines an object-oriented layer for the HTTP
specification.

Resources
---------

  * [Documentation](https://symfony.com/doc/current/components/http_foundation/index.html)
  * [Contributing](https://symfony.com/doc/current/contributing/index.html)
  * [Report issues](https://github.com/symfony/symfony/issues) and
    [send Pull Requests](https://github.com/symfony/symfony/pulls)
    in the [main Symfony repository](https://github.com/symfony/symfony)
