## Sandy.js

A Node Module That Allows You To Interact With Sandy Easily.

### Install 
`npm i sandy.js`

### Example Usage

```js
const sandy = require('sandy.js');
const client = new sandy.Client({ apiKey: 'API_TOKEN' });

console.log(client.get('GUILD_ID'));
```

#### Note :

- `API_TOKEN` and `GUILD_ID` is required.

### License 
`APACHE-2.0`
