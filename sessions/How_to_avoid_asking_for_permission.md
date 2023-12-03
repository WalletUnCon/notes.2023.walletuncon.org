---
Title: How to ask for permission?
Convener(s): depatchedmode, Agost Biro
---

## Notes

- We need advanced permission systems if we are serious about self-custody
- The problem: satisficing
- Optimizing vs Satisficing
    - *Optimizing:* user makes a conscisious decision by careful consideration of the problem
    - *Satisficing:* user takes the shortest path to achieve their goal
        - To *satisfy* your immediate needs, you *sacrifice* your informed consent.
        - Users are more likely to do this under time pressure, and the more information is presentd in a popup/confirmation.
        - This session is about how we discourage satisficing user behavior.
- Solutions



| Solution | Web2 | Web3 |
| -------- | -------- | -------- |
| Reduce prompts     | Automatic grants, Trusted UIs     | Intents, Implicit grants, Trusted UIs?     |
| Delay permission requests     | Contextual prompts     | Contextual prompts?     | 
| Isolate apps | Site-specific authentication | Special-purpose keys |



- **Reduce the number permission prompts**
    - Web2:
        - *Automatic grants* 
            - For low impact, reversible actions 
            - E.g. set wallpaper
        - *Trusted UIs*
            - Operating system helps the user to carry out task securely
            - Part of the natural usage flow of the user
            - E.g. photo picker in iOS
    - Web3:
        - *Intents*
            - Web3-native solution to bundle multiple transactions into one permission prompt
        - *Implicit grants*
            - Follows the principle of trusted UIs: "permission" is granted by the user carrying out a desired action
            - E.g. instead of granting a token approval to a USDC payments app, transfer the tokens to an app-specific address.
        - *Trusted UIs*
            - Much more difficult in Web3 than in Web2, because
                - duplicate prompts between dapps and wallets
                - fragmentation of the ecosystem: different wallets and dapps have to coordinate instead of a closed ecosystem enforcing policy

- **Delay permission requests until user is in flow that facilitates optimizing behavior**
    - Web 2:
        - *Contextual runtime prompts*
            - Instead of asking for permissions at install time, ask for one specific permission when the user carries out an action the relevant action
            - E.g. prompt the user for location access when they want to see their location on a map
    - Web 3:
        - *Contextual runtime prompts*
            - E.g. imagine a decentralized social network that has a permission system for accounts. When the user connects their account to a third-party app, it only asks for posting permission when the user actually performs an action that creates a post
            - Difficult, because the third-party app might not be able to prompt the wallet/authentication app when the user tries to carry out the relevant action
- **Isolate app interactions**
    - Web2:
        - *Site-specific authentication*
            - Site-specific credentials to prevent compromise of a single malicious website from compromising other websites
            - Automate the idenfication of websites to prevent users from exposing their credentials to malicious websites
            - E.g. password managers, passkeys
    - Web3:
        - Special-purpose keys
            - Prevent malicious dapps from stealing tokens
            - Allow automatic transaction approval
            - *App keys*
                - Web3 apps on mobile often create their own externally owned accounts (EOA) or smart contract wallets (SCW) to automate signature approval
                - E.g. Farcaster
                - Challenges:
                    - App needs to take care of key recovery
                    - For usage of the key beyond the app, the app has to add wallet-like functionality
            - *Session keys*
                - SCW creates a scoped ephemeral key
                - Challenges:
                    - How SCWs identify dapps (smart contract address) and how user identify dapps (domain name) is misaligned
                    - SCW needs to interpret transaction parameters signed with session key
            - *Dapp keys*
                - Wallet creates EOA for a dapp (bound by domain name)
                - Challenges:
                    - Needs balance to pay for gas
                        - Solved by [EIP-3074](https://eips.ethereum.org/EIPS/eip-3074) (AUTHCALL)
                    - Many dapps expect one EOA/user
- Discussion
    - *ENS domain binding* idea
    - Binding trusted UIs to smart contracts
        - Challenge: composability
    - EIP-6963
    - Drag-and-drop permissions

- Sources
    - https://www.usenix.org/conference/hotsec12/workshop-program/presentation/felt
    - https://www.paradigm.xyz/2023/06/intents

- Follow up discussion: https://github.com/ChainAgnostic/secure-design/discussions

## Links

- Emily Starks Talks about secure UI design in browsers - https://emilymstark.com/speaking.html
