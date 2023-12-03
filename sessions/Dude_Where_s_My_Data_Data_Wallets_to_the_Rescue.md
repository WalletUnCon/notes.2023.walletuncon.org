---
Title: Dude, Where’s My Data? Data Wallets to the Rescue
Convener(s): Matt Hamilton
---

## Notes

- intro presi
    - data structured acc to openSea standard used for metadata
    - If you lose your CID for data, you’re screwed. 
    - Looking for a standard to work across multiple systems. 
    - Like metamask, but with files and data. Not just NFTs - a metamask snap? E.g. RaaS with snaps
    - ERC 721s that represent your data, length of deal etc. (see proposed 'traits' of stored data in screenshot) 
    - Can the wallet allow you to manage the renewal/replication of your data?
- q&a
    - Building this on MM snaps would be compelling. You’d need to build a dapp that interfaces with the snap. A lot would need to be done on platform side to enable to show data visually in UI/UX of a snap.
        - In MM now, all data is local. When you restore your wallet’s state with the seed phrase, all data has to be restored. The amount of local state in wallet will increase in the future. 
        - We need to find different ways to retrieve the same data from multiple clients, especially if you lose local versions of it. 
        - Storage capacity is a challenge for snaps. Syncing between different versions of MM (e.g. mobile, desktop etc.) is also an issue. 
        - There is currently replication of data on Filecoin, available as a snap
        - Decentralized ways to solve this would be cool, especially with IPFS. 
        - How about a decentralized identifier. PKH DID accounts as a solution? We need a sovereign data model for sure.
    - Did you consider DAG in this process and how to deal with versioning of data?
        - As your data changes on different devices, without sync. Libp2p polytrees could be a solution to sync DAGs.
        - OR store it as a list on a smart contract and keep track of the smart contract. 
        - OR create a graph of those with one CID to bind them all. 
    - Ceramic network could be a solution 
        - Data stream platform with different streams for different data you wanna store. Owner of DID can push this data and share this data as IPFS is needed. 
    - Preference for all this to be standardized. 
        - Working in the open to sync on a standardize. Its an envelope for CIDs to be pluggable into other ecosystems. IPLD instead of IPFS would be an issue if we are just using CIDs. Use chain agnostic network proposals to discuss this, since this is an underlying need for the ecosystem.
    - Privacy would be an issue too. 
        - If wallet address is known, CIDs can be found and data is compromised. 
 

Did you consider DAG in this process and how to deal with versioning of data?
As your data changes on different devices, without sync. Libp2p polytrees could be a solution to sync DAGs.
OR store it as a list on a smart contract and keep track of the smart contract. 
OR create a graph of those with one CID to bind them all. 
