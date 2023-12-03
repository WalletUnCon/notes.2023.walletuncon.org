---
Title: EOA Alchemy: migrating to smart contract wallets
Convener(s): @lightclient 
---

## Notes

- EIP 4337
    - we ain't enshrining it sweetie 
- EIP 7377 or EIP 5003 - deploy code at your EOA
- EIP 3074 - slay
- EIP 7553 (number not assigned yet) - sponsored transactions


####  UX-level changes

- EIP 7555 abstracts this??
- push to the libraries (ethers/viem) for batching user ops / fallback to eoas 
- 6963 : multi injected provider

- prioritization framework: how many people do we actually have to migrate?
    - https://etherscan.io/chart/active-address
