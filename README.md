# Crypto indexes

Live demo: https://bdav24.github.io/crypto-indexes/index.html?from=0&to=10
(edit `from` and `to` query params to add or remove pairs)

## Under the hood

1. Get crypto prices from https://api.coinmarketcap.com/v2/ticker/ ordered by rank.
2. Filter prices from `from` to `to` parameters.
3. Create the index, which os the sum of `ALTBTC / "its price in BTC"`.
4. Use the index in https://www.tradingview.com for example.
