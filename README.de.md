# url_extractor

Dieses Modul für UliCMS 2018.4 und neuer extrahiert URLs aus einem String
und gibt diese als Array zurück

## Example

```php
<?php
$extractor = new UrlExtractor();
$urls = $extractor->fromString("This is a string with a link https://www.google.de");
var_dump($urls);
```
