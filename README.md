**Note: I don’t intend to maintain this package. [Other copies](https://packagist.org/search/?q=simple-html-dom) of Simple HTML DOM are already available on Packagist, are easier to install and don’t clutter your `composer.json`
file.**

simple-html-dom
===============

A copy of the [PHP Simple HTML DOM Parser project](http://simplehtmldom.sourceforge.net/) usable as a [Composer](http://getcomposer.org/) package.

## Installation

First, you need to add this repository at the root of your `composer.json`:

```json
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/Youpie/simple-html-dom"
    }
]
```

Then, require this package in the same way as any other package:

```json
"require": {
    "simple-html-dom/simple-html-dom": "*"
}
```

Do a `composer validate`, just to be sure that your file is still valid.

And voilà, you’re ready to `composer update`.

## Usage

Since this library doesn’t use namespaces, it lives in the global namespace.

```php
$instance = new \simple_html_dom();
```

Check the [official documentation at SourceForge](http://simplehtmldom.sourceforge.net/manual.htm).
