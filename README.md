# rfc-js-object-shorthand-path
A proposal for JS object shorthand with paths.

See also [rfc-js-declaration-identifier-from-leaf](https://github.com/AndersDJohnson/rfc-js-declaration-identifier-from-leaf).

Use the last token in an access path as the name of the key in the object.

```js
const obj = {
  window.location,
  window.document.title
};
```

would be equivalent to:

```js
const obj = {
  location,
  title
};
```
