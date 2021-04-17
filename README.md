<h1>Parsedown (forked by Dotteex)</h1>

Forked Parsedown (markdown parser) which adds a cleaning function. See example below.

## Example

```php
$Parsedown = new Parsedown();

echo $Parsedown->clean('Hello _Parsedown_!'); # prints: Hello Parsedown!
```

Forked from <a href="https://github.com/erusev/parsedown">erusev/parsedown</a>.