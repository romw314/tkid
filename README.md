# TkID

TkID is an easy way to generate tokens or IDs.

## Usage in browsers

```html
<!DOCTYPE html>
<html>
  <head>
    <script src="https://cdn.jsdelivr.net/npm/tkid/index.js"></script>
  </head>
  <body>
    <script>
      // generate a random token
      const token = tk();
    </script>
  </body>
</html>
```

## Usage in Node.js

Install:

```sh
npm i tkid
```

Use:

```javascript
const tk = require('tkid');

// generate a random token
const token = tk();
```
