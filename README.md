# Package Preamble

Generates a minimalist preamble from a package.json. For example, given a package.json file:

```json
{
  "name": "hello-world",
  "version": "0.0.1",
  "homepage": "https://example.com/hello-world/",
  "author": {
    "name": "Alice Baker",
    "url": "https://example.com/alice"
  }
}
```

If you run preamble:

```
preamble
```

You’ll get the following output:

```js
// https://example.com/hello-world/ Version 0.0.1. Copyright 2016 Alice Baker.
```
