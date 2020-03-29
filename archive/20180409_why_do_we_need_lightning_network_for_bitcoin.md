### Why do we need Lightning Network for Bitcoin?

Because the Bitcoin blockchain is too slow and expensive to use for microtransactions and beause sidechains do not solve the problem.

**TL;DR**:

It takes too long to mine a block and that also makes it too expensive to do many transactions per second on the Bitcoin Blockchain.

Some have proposed making larger blocks or changing the way information is stored in each block to allow more and faster transactions. 10x the blocksize for example does not really solve the problem - it would still be too slow/expensive.

One answer to this question is to use sidechains - ie transact on a "local" currency that is fast and cheap. For example Starbuckscoin.

To enable you buying a coffee using Starbuckscoin at your local Starbucks, you would first have to acquire such a Starbuckscoin - which means you would have to spend Bitcoin to get Starbuckscoin. That does not solve the problem - it just displaces and increases it. You would still have the wait and have to pay the fees relating to the Bitcoin Blockchain and on top of that, you would have to have all sorts of local currencies for each merchant you are dealing with.

Lightning Network works just like a the cashbox in a shop. The reason to have a cashbox in a store is to avoid the merchant having to travel to the bank every time someone buys a coffee from him. Instead he keeps the cash in the cashbox or register until the end of the day, week, whatever.

So, essentially Lightning Network is this cashbox. Two parties can share a cashbox. In the Starbucks example I could have a private cashbox (called Channel in LN) and we would only settle against the Bitcoin Blockchain once per month. Or we could even have one big shared Cashbox where all the customers and vendors of Starbucks settle locally before settling on the Bitcoin Blockchain.

The clever thing about LN is that it does not require the parties in the channel to trust eachother

References

https://cointelegraph.com/explained/lightning-network-explained
https://en.wikipedia.org/wiki/Bitcoin_scalability_problem
https://en.bitcoin.it/wiki/Block_size_limit_controversy
