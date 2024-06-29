# browser-bundles
Bundled NPM Modules

**buffer.js**  [Download](https://github.com/SolDapper/browser-bundles/blob/main/buffer.js)
```html
<script src="/path/to/your/buffer.js"></script>
<script>
const Buffer = require("buffer").Buffer;
// Buffer.from("swap-state");
</script>
```
**bn.js**  [Download](https://github.com/SolDapper/browser-bundles/blob/main/bn.js)
```html
<script src="/path/to/your/bn.js"></script>
<script>
const BN = require("bn.js");
// new BN(decodedStateData.fee, 10, "le").toString();
</script>
```
**bs58.js**  [Download](https://github.com/SolDapper/browser-bundles/blob/main/bs58.js)
```html
<script src="/path/to/your/bs58.js"></script>
<script>
// bs58.encode(tx.serialize());
</script>
```
**splToken.js**  [Download](https://github.com/SolDapper/browser-bundles/blob/main/splToken.js)
```html
<script src="/path/to/your/splToken.js"></script>
<script> console.log(splToken.TOKEN_PROGRAM_ID); </script>
```
