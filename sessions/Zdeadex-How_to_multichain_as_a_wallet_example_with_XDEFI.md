# Notes for session D4 at WalletUncon 2023

Title of talk: Zdeadex - How to multichain as a wallet, example with XDEFI
Convener(s) of talk: 
Scribe(s) of talk: HarryR - github.com/CedarMist / github.com/HarryR
Links to any presentation matter:

Tips:
- if you use github or gitlab handles instead of names, that allows scribes and conveners to be easily findable/taggable in threads when these notes get published to the CASA github org)
- preface remarks with name/handle and org if you WANT to be credited for contributions or ideas. 
- feel free to call multiple people "anon" if you don't catch their names or they do not give them
- most scribes love an assist!

XDEFI Wallet
 - Supports all types of chains
 - We should improve what we have because there is no standard at all
 - Lets figure out how to build it

It's very hard when you have multichain, with one chain it's much simpler.

It's important to understand about wallet integration. And interoperability.

The UI/UX, it's not very simple to just show the token and which chain it's on.

What's the future of multi-chain wallets?


## Notes

- heirachical notes recommend
    - for capturing flow

- Maintaining many blockchains
  - How can we work on that?
  - Users want privacy, and they want the wallet developers to maintain it
    - So, we end up building a custom RPC endpoint, for multi-chain wallets
  - For privacy:
    - Don't reveal the communications between clients and RPC endpoints
  - Need to maintain indexers for all of the supported blockchains
  - We aspire that protocols can be run on a local device, to verify trustlessly
    - With a ZK light-client, we can trustlessly verify the data is correct
  - [Query Incentive Networks](https://www.cs.cornell.edu/home/kleinber/focs05-qin.pdf)
    - Can add a referral fee along the graph
    - Creates a race to bring prices down across the network
    - e.g. if you run your own geth node at home, and give a few friends access (but they're metered / bandwidth limited), and may even ask them to give you beer money for providing them with a trusted node
  - Solving for price, latency and a variety of other variables


If all the wallets build it in the same way it makes it easier.
Apps want to see historical data, you must host archival nodes. 200 archive nodes is a huge overhead. With blobs we'll have many L2s.

Chains like plasma or binance, which prioritise speed over decentralization, will be stupidly expensive to run archival nodes. When somebody connects to a new chain, to have good decentralized optoins (some chains have no good decentralized options)

If there's only one endpoint, and you end up using the public one, you don't really have any privacy. 

Once you go to Solana / Cosmos, there are different signing algorithms. We could do with a standard implementatoin of all the signers.

It's very difficult to build support for all of the signers & algorithms, abi encoding, RPC formats etc.

Somebody was pushing machine-readable documents for RPC. There could be a .well-known URL which describes the JSON-RPC format, a self-describing interface, where you can query the capabilities of the JSON-RPC.

What if each service can provide an object which represents its capabilities, e.g. 'name' key which is the name of the service. A provider can ask for 'an ethereum provider' - each service self-identifies. How do you type check & type-enforce, which has a reserved key - e.g. every service can register as many type keys as it wants, and a requesting service can be specific with what it wants with the type definitions.

e.g. if your wallet is a contract account there will be a specific key that indicates it.  e.g. early on Ledger didn't support EIP-712, which made it really complex.

Need somebody to define what the typing standard is. Runtime type descriptors.

## UI / UX

Less data in the front, presented to the user?

.e.g. if there's a token on the chain, e.g. BTC on Bitcoin, how can you standardise this vs BTC on Ethereum. If you have USDC on 4 different chains, the wallet may see your total USDC balance, and can 'show more details' to show the specific chains the tokens are on.

When grouping you want to know who to trust to specify which tokens on which chains are equivalent, otherwise somebody could create a fake token which shows up as real money if you grouped by e.g. the ticker name alone.

So like what chainlink does with CCIP, interacting with one blockchain and another. You can be on Polygon, and do something on Ethereum. Paying gas remotely.

Account abstraction, how can we solve the gas problem. http://rabby.io/ ?

## Links

- [description](https://example.com)
* https://eips.ethereum.org/EIPS/eip-6963