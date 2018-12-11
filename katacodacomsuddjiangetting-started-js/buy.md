Buying a stock is easy. Let's go ahead and try that now.

<pre class="file" data-filename="main.js" data-target="append">

alpaca.createOrder({
  symbol: 'SPY', // choose your own stock to buy here
  side: 'buy',
  qty: 1,
  type: 'market',
  time_in_force: 'gtc',
}).then(order => console.log('You just ordered: ', order))
</pre>

You can run the script again with `node ./main.js`{{execute}}
