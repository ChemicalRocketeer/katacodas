Buying a stock is easy. Let's go ahead and try that now.

<pre class="file" data-filename="main.js" data-target="append">

alpaca.createOrder({
  symbol: 'SPY', // choose your own stock to buy here
  side: 'buy',
  type: 'market',
  time_in_force: 'gtc',
}).then(order => console.log(order))
</pre>
