# backrunner

- [x] watch transactions from specific addresses in the mempool
  - [x] uniswap trades; addresses TBD
- [x] craft a backrun arb
- [x] write arb executor contract
- [x] ~~execute~~ simulate arb using Flashbots

## iterations

The base repo is empty. Check out one of the following branches:

None of these are quite done or functional, but they provide a general structure and approach for backrunning, and may be useful for learning.

* [empty project](https://github.com/zeroXbrock/backrunner/tree/skeleton)
* [the one I made at home for practice](https://github.com/zeroXbrock/backrunner/tree/hack1)
* [the one I wrote live](https://github.com/zeroXbrock/backrunner/tree/hack2)

> :warning: Running a mempool backrunner can be risky. There are poison tokens that drain your liquidity when you trade them. See [salmonella](https://github.com/Defi-Cartel/salmonella) for an example.
