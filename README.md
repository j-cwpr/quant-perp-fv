## Perpetual Future Fair Value Estimation

### Outline
- build a fair value engine that takes in order book and oracle data for a given perpetual future
- update the fair value incrementally as input data changes
- quote a bid and offer around the fair value and validate against the book and trades

### Research Question
- does using an incrementally updated fair value estimate a perpetuals future short term horizon better than using the mid and thus improve quoting?

### Specification and Data
- target listed perpetuals on Hyperliquid: BTCUSDc, ETHUSDC
- historical order book data from Tardis
- live data from Hyperliquid websocket
