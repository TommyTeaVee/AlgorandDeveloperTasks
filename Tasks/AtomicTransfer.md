## Task: Atomic Transfers

In this task, you will trade in 5 of the [DevCoins](https://github.com/algorand-devrel/AlgorandDeveloperTasks/blob/master/Assets/DevCoins.md) you earned in [this task](https://forum.algorand.org/t/task-opt-in-to-asas/1151), for a new shiny [Atomic Transfer Badge](https://github.com/algorand-devrel/AlgorandDeveloperTasks/blob/master/Assets/AtomicTransferBadge.md). You will do this by creating... 🥁, you named it, an Atomic Transfer between these two Assets. 

We have placed the Atomic Transfer Badges into an Algorand Smart Contract Account with logic that allows you to trade in 5 DevCoins in exchange for 1 badge. It's up to you to create this group transaction, submit it, and earn a badge!

The Smart Contract Account that has the badges is here: `MJXF5ZZAIZKHEHQD324UEWXID3TQMPOF7P52PXSCEJBH66TKNATAEVMIHU`.

Its associated LogicSig can be accessed here: https://github.com/algorand-devrel/AlgorandDeveloperTasks/blob/master/Contracts/atb.lsig

### Task instructions
1. Make sure you have completed the [Task: Opt-in to ASAs](https://forum.algorand.org/t/task-opt-in-to-asas/1151) to get 10 DevCoins.
2. Opt-In to the Atomic Transfer Badge Asset. Details [here](https://github.com/algorand-devrel/AlgorandDeveloperTasks/blob/master/Assets/AtomicTransferBadge.md).
3. Create a group transaction with 2 transactions (order matters). 
   1. **Transaction 1**: Asset Transfer of 5 DevCoins from you to the Smart Contract account.
   2. **Transaction 2**: Asset Transfer of 1 AtomicTransferBadge from the Smart Contract Account to you.
4. Group these transactions, i.e. calculate the group ID and assign it to each transaction before signing.
5. Sign the first transaction with your secret key.
6. Attach the LogicSig to the second transaction as its signature. Note that this is different from the usual way you would sign a transaction and will be represented differently in the SDKs.
7. Submit them together to the network.
8. If done right, the badge will belong to you in less than 5 seconds!

#### Prerequisites
1. Read how Atomic Transfers work [here](https://developer.algorand.org/docs/atomic-transfers).
2. Check out how to use Algorand Standard Assets in [Go](https://developer.algorand.org/docs/atomic-transfer-sdk-usage#go), [Java](https://developer.algorand.org/docs/atomic-transfer-sdk-usage#java), [JavaScript](https://developer.algorand.org/docs/atomic-transfer-sdk-usage#javascript), and [Python](https://developer.algorand.org/docs/atomic-transfer-sdk-usage#python).

### Hint
This Atomic Transfer is enabled by a Smart Contract account, but it does _not_ require you to author or change any contracts. We will save that for another time! 

All you need to know is that in order to sign the transfer _from_ the Smart Contract account, you must attach the program bytes, called the LogicSig. Those can be found [here](https://github.com/algorand-devrel/AlgorandDeveloperTasks/blob/master/Contracts/atb.lsig). 

### Why This Task Matters

Atomic Transfers paired with Algorand Smart Contracts mean that you can create logic that will allow anyone to trade for your asset provided they give you something in return. Once the contract is funded, this is essentially a no-touch solution for the seller and a single group transaction for the buyer. This task is very similar to a limit-order trade. 

The combination of Assets, Atomic Transfers, and Layer-1 Smart Contracts can be very powerful and makes transfers like these very fast and secure. This is just one of the many different use cases that is made possible by these new features. 

### Have Questions?
Post them here!
