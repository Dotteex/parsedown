<h1>Parsedown</h1>

Forked Parsedown (markdown parser) repository with a markdown removal function. See example below.

## Example

```php
$Parsedown = new Parsedown();

echo $Parsedown->clean('Hello _Parsedown_!'); # prints: Hello Parsedown!
```

Forked from <a href="https://github.com/erusev/parsedown">erusev/parsedown</a>.
