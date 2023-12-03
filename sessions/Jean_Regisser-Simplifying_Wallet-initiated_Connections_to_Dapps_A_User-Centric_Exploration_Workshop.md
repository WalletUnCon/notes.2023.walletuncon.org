---
Title: Simplifying Wallet-initiated Connections to Dapps -- A User-Centric Exploration Workshop
Convener(s): Jean Regisser ([@jeanregisser](https://github.com/jeanregisser/))
Scribe(s): Tanya (Safe)
Slides: https://docs.google.com/presentation/d/156WKnzDIyMNvzVR4ADvaMJSgetMUNxpSPR9y4QA9FJs/edit?usp=sharing
---

## Abstract

Ever opened a dapp directly from your wallet, and struggled to connect as you were confronted with a laundry list of wallet choices? When it’s crystal clear which wallet is being used. It's a real buzzkill, and it's causing a whopping 70% drop-off rate. We're all about simplifying the process, aiming for one-click (or even zero-click) connections. Join us in this workshop as we explore solutions to this and garner support for drafting an Ethereum Improvement Proposal (EIP) to make dapp connections a breeze. Inspired by EIP-6963, but not confined to injected providers.

## Notes

User starts a journey in a dapp browser, they click on e.g. Uniswap and their page might look confusing because they need to connect again, they open the connection modal, click on WalletConnect — see another WC connection popup, and they search for the wallet they started a journey in.

Once it’s connected, Uniswap still shows prompts to download their wallet. 

There is 70% users drop-off. 

So the question is: how to go from the Dapp browser page to the successful connection screen in less steps?

Discussion:
1. Switching back and forth between dapps to connect is very confusing.
2. Logging in e.g. Portfolio from Metamask wallet is principal: making a boundary between being neutral and having such a power. 
3. Sometimes the connection simply doesn’t work, after the request is initiated.  
4. Interaction may be very different based on what you’re doing as a user and where you are (e.g. sometimes we do things while commuting, etc.) 
5. We can remember the last connected wallet ideally 
6. It would be a dapp developers’ responsibility to recommend what to connect to
7. First time you interact with a dapp they don’t know your identity just yet, but once it’s a common interaction
8. There needs to be an agreement between the connection libraries and wallets
9. Strategic mapping of partners is important to understand who’s responsible for what sort of control — in order to make structural change
10. EIP-6963 could help but only works for injected providers. And doesn't (yet?) support autoconnect.
11. On iOS, some wallets offering a section to explore dapps have to open them in the external browser, to comply with Apple's review guidelines. So injected providers can't be used, unless these wallets build a mobile safari extension.
12. We could pass the wallet details and connection method (injected provider, WalletConnect, or a future connection mechanism) to the dapp being opened (via URL parameters or User-Agent). Connection libraries (Web3Modal, RainbowKit, Blocknative) could use this information to either directly connect the specified wallet (autoconnect) or show only the wallet when the user taps the connect button.

Solution:
- Create a collaborative effort to create a better onboarding, that would pick the preferred wallet, etc. 
- Collaborative funding (grant?)
- Build dapps to align with what other wallets
