# stock-screener-for-option-trading-v1

So basically I was browsing reddit and found someone mentioned a strategy that they use before buying call options.

So here's the code to screen stocks according to that strategy,

Here are all the checks for B-Score. If they are True, the counter gets increased by 1.

- RSI <=40

- Volume >=100

- Filled price <= Lower Bollinger band

- SMA ( 5 days) <= VWAP

- Spread >=0.05 (This might change in future)

- Filled price = Current Bid

- IV<=40

- Today gain <= 0
