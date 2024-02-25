# Collection of useful syntaxes in Javascript

## Logical validation

### Used when we want to compare two values; if two values are the same, it will return true; if not, a string will return.
```javascript
const value = 'foo';
const value === 'bar' || "This value is not the same."
// This value is not the same.
```

## Snippets

### Filter falsy value
```javascript
const arrayNames = ["Adam", "Eva", null, ''];
const filterNames = arrayNames.filter(Boolean)
// ["Adam", "Eva"];
```
