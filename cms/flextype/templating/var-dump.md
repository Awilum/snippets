Dump data in Flextype Twig Templates with help of built-in Arrays Component helper function `arrays()`

```twig
{% do arrays(flextype.entries.fetch('blog', {'collection': true})).dump() %}
```

https://atomastic.com/components/arrays/methods/dump
