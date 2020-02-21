# helloWorld...
Friendly User
/ in node.js use: var Web3 = require('web3');

var web3 = new Web3(Web3.givenProvider || "ws://localhost:8545");
import "@openzeppelin/contracts/GSN/GSNRecipient.sol";

contract MyContract is GSNRecipient, ... {

}
Installation :
```bash
npm install @remixproject/plugin
```

or with a unpkg :
```html
<script src="https://unpkg.com/@remixproject/plugin"></script>
```

### Plugin Client
The plugin client is how you connect your plugin to remix.

To import ( the ES6 way) with NPM use:
```javascript
import { createIframeClient } from '@remixproject/plugin'
const client = createIframeClient()
```
Or if you are using unpkg use:
```javascript
const { createIframeClient } = remixPlugin
const client = createIframeClient()
```
