First, let's install the Alpaca API from npm.

Run `npm install @alpacahq/alpaca-trade-api`{{execute}}

Now, we can import and initialize the api

<pre class="file" data-filename="app.js" data-target="replace">
const Alpaca = require('@alpacahq/alpaca-trade-api')
const alpaca = new Alpaca({
  keyId: // Paste your key id here
  secretKey: // Paste your secret key here
  paper: true
})
</pre>
