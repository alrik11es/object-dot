# object-dot-notation library

![Status](https://travis-ci.org/alrik11es/object-dot-notation.svg?branch=master)

The idea behind this library is to allow the access through `config.port` dot notation to object data.

## Installation

Requires composer and PHP7.0+

> $ composer require alrik11es/object-dot-notation

## Usage

Simple usage:

```php
$d = Data::load($mixed);
$d->get('config.port');
```