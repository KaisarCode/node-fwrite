# FWrite
[nodejs] fs.writeFileSync wrapper.

### Install
```
npm install kc-fwrite
```

### Use
```js
var fwrite = require('kc-fwrite');
var mod = 0o644; // Permissions (default: 0o755)
fwrite('file.txt', 'Hello', mod);
```
