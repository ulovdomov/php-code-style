# php-code-style
This package contains rulesets for PHP Code sniffer which used by UlovDomov PHP Apps.

| Supported version |  Ruleset filename  |
|-------------------|--------------------|
| PHP 8.0+          | ruleset.xml        |

## Usage
Replace <src> with your source code destination
```shell script
php vendor/bin/phpcs app --standard=vendor/ulovdomov/php-code-style/ruleset.xml <src>
```

For code sniffer autofixation run
```shell script
php vendor/bin/phpcbf app --standard=vendor/ulovdomov/php-code-style/ruleset.xml <src>
```
(replace phpcs with phpcbf)

## Advanced usage

* For better usage insert commands in `composer scripts` section in your project composer.json.
* Add `--cache <path>/<to>/<cache>/<file>` to improve code sniffer speed
