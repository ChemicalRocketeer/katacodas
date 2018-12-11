First, let's install the Alpaca API from npm.

Run `npm install @alpacahq/alpaca-trade-api`{{execute}} to install the API.

Now, we can import and initialize our Alpaca module.

<pre class="file" data-filename="main.js" data-target="append">

const Alpaca = require('@alpacahq/alpaca-trade-api')
const alpaca = new Alpaca({
  keyId: YOUR_KEY_ID, // Paste your key id here
  secretKey: YOUR_SECRET,// Paste your secret key here
  paper: true
})
</pre>

To start, let's just get your account info.

<pre class="file" data-filename="main.js" data-target="append">

alpaca.getAccount().then(account => console.log(account))
</pre>

We can run this code with `node ./main.js`{{execute}}
