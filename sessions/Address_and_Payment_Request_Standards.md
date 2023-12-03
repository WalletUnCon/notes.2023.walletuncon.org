# Notes for session C2 at WalletUncon 2023

Title of talk: Address and Payment Request Standards
Convener(s) of talk: DC Posch, Nalin B 
Scribe(s) of talk:
Links to any presentation matter:

Tips:
- if you use github or gitlab handles instead of names, that allows scribes and conveners to be easily findable/taggable in threads when these notes get published to the CASA github org)
- preface remarks with name/handle and org if you WANT to be credited for contributions or ideas. 
- feel free to call multiple people "anon" if you don't catch their names or they do not give them
- most scribes love an assist!

## Notes

- Agenda and scoping
    - the main problem is that receiving funds can be ambiguous and complicated in a multichain world. 
    - The aim of this discussion is to figuring out the options for unambiguously sending, we will especially focus on links as a tool for resolving these complexities
- Sending funds can also be done via links
    - To fix the multichain ambiguouty, we have the EIP-3770 option which is to pre-pin the name of the chain, e.g. eth:0x...
    - This should be a discussion about the options around creating a standard
- Round of questions
    - Why are testnet addresses and non-testnet addresses different?
        - no good answer
    - Why is no one using EIP-3770?
        - no non-obvious answer (little cross ecosystem movement)
- Discussion
    - Users lose funds because they get the chains wrong
    - Keystore contracts have many disadvantages
    - URLS
        - URLs can be carry the information
        - Payments and Request links exists
        - web3 URI
            - using the web3:// URI would be one option, could be any URI (https://ethereum-magicians.org/t/standardize-url-format-for-web3-browsers/2422)
        - how do we be credibly neutral with domains?
            - eth.link or similar?
        - These URLs should resolve automatically
    - Users should have to be able to state preferred tokens and chains 


## Links

- [ERC 3770](https://eips.ethereum.org/EIPS/eip-3770)
- [web3:// URI](https://ethereum-magicians.org/t/standardize-url-format-for-web3-browsers/2422)
- Projects with claim links: [Daimo](https://daimo.com), [Peanut](https://peanut.to)