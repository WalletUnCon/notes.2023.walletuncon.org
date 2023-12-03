# Notes for session A4 at WalletUncon 2023

Title of talk: Using threshold ECDSA and passkeys as the foundation for browser-based wallets
Convener(s) of talk: Andronikos Nedos
Scribe(s) of talk: Ryan Betts (@depatchmode)
Links to any presentation matter: 
Also present: Kyle, Hester, Lefteris, Yabir

## Notes

- why threshold ecdsa + passkeys?
    - self-custodied browser based wallets are hard
    - where to put the keys?
    - concerns about browser security model: who can read the private key?
        - Kyle: what about WebCryptoAPI?
        - keys are not exportable. great!
        - but how to get authenticated on other devices? root of authority trapped in browser
        - wrapKey api might allow this to be portable
    - passkeys provide an alternative to key management
        - there's tension between OS key management solutions, vs cross-platform KMS like 1Password
    - MPC threshold ECDSA
- how is passkey recovery handled?
    - can be protected against by authenticating passkeys from multiple devices
    - each service could also decide on its own process for allowing re-linking of an identity to a new passkey
- how future proof is this to new curves, etc?
    - this would require extensions and moving through the w3c standards process
    - prf extension is an example right now: enables passkey use for not just signing but encryption
- wallet as a passkey?
    - a wallet could support passkeys (act as a WebAuthN provider) in the same way that it supports multiple networks (see CAIP-2 + 10)
    - those passkeys could then be rooted for recovery in the recovery phrase
    - also the recovery phrase could be replaced in a wallet by a passkey; just wallet just requires the PRF spec to land in a wallet
- can passkey be used to sign on ethereum?
    - requires signature validation of a non-native curve
    - there is EIP-7212 precompile
- how does this fit into TSS? 
    - DKG would split shares
    - could a passkey be a holder of a share?
    - OR instead of a mathematical threshold, what about a programmatic threshold? only affordable if off-chain 

## Links

- [description](https://example.com)