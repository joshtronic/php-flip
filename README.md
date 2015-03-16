# php-flip

PHP port of [flip.js][flipjs]

## Installation

To install via `composer`, add the following to your `composer.json`:

```
"require": {
      "joshtronic/php-flip": "dev-master"
}
```

Then run `composer update`

## Usage

```php
$flip = new joshtronic\Flip;
echo $flip->flip('text to flip');
```

[flipjs]: https://github.com/jergason/flipjs/blob/master/flip.js
