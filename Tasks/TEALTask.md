## Task: Build an Algorand Smart Contract

In this task, create an Algorand Smart Contract in TEAL that solves any problem you choose. Reply to this post with a description of the problem you are trying to solve, the commented TEAL code that solves the problem, and any further explanation (e.g. caveats, pitfalls) that the user should be aware of if they use the code. The contract can be as short or as long as you want. The point of this task is to get you familiar with TEAL opcodes and provide a platform for discussing use cases and best practices.

_Need a suggestion for a problem to solve? How about a recurring payment? Write a Smart Contract that allows someone to remove no more than **x** Algos from your account every **y** blocks._

### Task instructions

1. Write your TEAL program.
2. Make sure it compiles and that you successfully test a transaction against it on TestNet.
3. Reply to this [post](https://forum.algorand.org/t/task-build-an-algorand-smart-contract/1188) with a description of the problem you are solving, the TEAL code you wrote to solve it (with inline comments), and any further explanation of pitfalls or caveats that you think are relevant.
4. Earn the Algorand [TEAL Badge](https://forum.algorand.org/badges/109/teal-badge) by participating in this task.**
5. (optional) To receive an on-chain version of the TEAL Badge, include an Algorand address in your post that has opted-in to the asset. Asset details [here](https://github.com/algorand-devrel/AlgorandDeveloperTasks/blob/master/Assets/TEALBadge.md).

**Participation means that you post a reply with the specified information, that your script compiles successfully, and it is accurately explained. If your contract has pitfalls or issues that you did not callout initially, the badge can still be earned through engaging in discussion related to feedback about your submission.

#### Prerequisites

1. Checkout this [Medium post](https://medium.com/algorand/understanding-algorand-smart-contracts-b9fc743e7a0f) for getting started with Algorand Smart Contracts
2. Review the [Algorand Smart Contract documentation](https://developer.algorand.org/docs/asc) to learn more about how ASC1s work in `goal`.
3. For testing your Smart Contract, use `goal` or any of the [SDKs](https://developer.algorand.org/docs/asc1-sdk-usage).

### Hint

Take a look at the templates that Algorand [has created](https://github.com/algorand/go-algorand/tree/master/tools/teal/templates) for inspiration.

### Why This Task Matters

With Algorand Smart Contracts you can create contract accounts for escrow-like payments or you can delegate signature authority to authorize withdrawals from an account. Both of these scenarios are backed by an Algorand Smart Contract written in TEAL.

Algorand will provide the community with templates that represent common use cases, but you can also create your own TEAL code to apply to various other use cases. When delegating a signature, this can be very powerful but also very dangerous. Learning what you must check for to protect an account is very important.

### Have Questions?

Post them here!

