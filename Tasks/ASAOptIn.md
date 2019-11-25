## Task: Opt-In to ASAs

In this task, use `goal` or any of our SDKs, to opt-in to receive the Algorand Standard Asset called [Algorand Developer Coins](../Assets/DevCoins.md) with Asset ID `3797`.

### Task instructions
1. Issue an opt-in transaction for the asset id `3797` - AlgorandDeveloperCoins. 
2. Reply to this [post](https://forum.algorand.org/t/task-opt-in-to-asas/1151) with the **public address** that opted-in.
3. Within a few days, we will send you 10 DevCoins on TestNet! Hang onto the coins. We may ask you to use them in future tasks. 

#### Prerequisites
1. Review the [Algorand Standard Assets documentation](https://developer.algorand.org/docs/asa) to learn more about how ASAs work in `goal`.
2. Check out how to use Algorand Standard Assets in [Go](https://developer.algorand.org/docs/asa-sdk-usage#go), [Java](https://developer.algorand.org/docs/asa-sdk-usage#java), [JavaScript](https://developer.algorand.org/docs/asa-sdk-usage#javascript), and [Python](https://developer.algorand.org/docs/asa-sdk-usage#python).

### Hint
An opt-in transaction is simply an Asset Transfer Transaction (TxType = `axfer`) with amount == 0 of the desired asset both `from` and `to` the account that wants to opt-in.

### Why This Task Matters

To receive a particular Algorand Standard Asset, an account owner must issue a transaction to opt-in to that asset. This ensures protection against users sending you assets that may somehow negatively impact you. 

### Have Questions?
Post them here!
