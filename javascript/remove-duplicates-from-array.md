# Remove Duplicates from an Array

Quickly remove duplicates from an array by leveraging spread operator and the `Set` object.

```
const array = ['foo', 'bar', 'baz', 'foo', 'bar', 'baz'];
const uniques = [...new Set(array)];
console.log(uniques); // ['foo', 'bar', 'baz'];
```

