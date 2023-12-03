# Notes for Coffee Break session at WalletUncon 2023

Title of talk: Rethinking the Wallet-Dapp Connection
Convener(s) of talk: Dan Finlay
Scribe(s) of talk:
Links to any presentation matter:

Tips:
- if you use github or gitlab handles instead of names, that allows scribes and conveners to be easily findable/taggable in threads when these notes get published to the CASA github org)
- preface remarks with name/handle and org if you WANT to be credited for contributions or ideas. 
- feel free to call multiple people "anon" if you don't catch their names or they do not give them
- most scribes love an assist!

## Notes

- conversational
- file picker / powerbox
- "authorize with blob" and redeem delegation
- langauge: how do we address this? only 18% of the world speaks any English
- very important to consider multiple languages, but also to understand context and intent and for an individual to communicate their wish in the correct technical language
- can LLMs help? LLMs miss too much context. Only information, no semantics. They can only do half the job of translation.
- What is the MVP of a site wallet connection?
    - "I want a token"...
    - Where should the trusted UI live? By circumstance has to be in the wallet client
    - What's the top level organization, in the file system metaphor?
        - Let's just plagiarize the file system
        - Should 
    - Goal is safety. If we use the "old method" we might not gain a safety improvement.
    - But adopting a breaking change SHOULD be avoided. Better to strongly incentivize movement to the new method.
- What role does rethinking account roles have?
    - if we make them too granular and remove them from userland as a core concept, do we mess up market dynamics and incentivize paymasters etc
    - This ties back to the questions of top level information architecture in the "file picker"
    - we go token-first because the wallet can make choices from there
    - "asset picker"
- General purpose question is: how does an account grant a permission?
- To what degree does the implementation of the contract (standard EOA, MPC, AA, multisig, etc) impact the experience of this granting?
    - shouldn't matter. in the end you're just granting a permission.
    - but there's some complexity in the UX for multisig 
    - take gnosis safe module for issuing session keys. add a general purpose method for how do get signers to respond to the request for asset permission
    - EIP-3074 is being done by 
- 

- 

## Links

- [description](https://example.com)
