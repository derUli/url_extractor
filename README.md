# url_extractor

This module for UliCMS 2018.4 and later extracts URLs from
strings and returns the urls as an array.

## Example

```php
<?php
$extractor = new UrlExtractor();
$urls = $extractor->fromString("This is a string with a link https://www.google.de");
var_dump($urls);
```
