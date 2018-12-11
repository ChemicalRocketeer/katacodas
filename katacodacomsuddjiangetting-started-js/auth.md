First, let's install the Alpaca API from npm.

Run `npm install @alpacahq/alpaca-trade-api`{{execute}}

Now, we can import and initialize the api

<pre class="file" data-filename="main.js" data-target="replace">
const Alpaca = require('@alpacahq/alpaca-trade-api')
const alpaca = new Alpaca({
  keyId: YOUR_KEY_ID, // Paste your key id here
  secretKey: YOUR_SECRET,// Paste your secret key here
  paper: true
})
</pre>
