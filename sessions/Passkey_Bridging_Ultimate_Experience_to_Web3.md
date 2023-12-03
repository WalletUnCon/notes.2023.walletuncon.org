# Notes for session F2 at WalletUncon 2023

Title of talk: Passkey: Bridging Ultimate Experience to Web3
Convener(s) of talk: Rui
Scribe(s) of talk: github.com HarryR / CedarMist
Links to any presentation matter:

Tips:
- if you use github or gitlab handles instead of names, that allows scribes and conveners to be easily findable/taggable in threads when these notes get published to the CASA github org)
- preface remarks with name/handle and org if you WANT to be credited for contributions or ideas. 
- feel free to call multiple people "anon" if you don't catch their names or they do not give them
- most scribes love an assist!

## Notes

SevenX Ventures, invested in flashbots, dodo etc. infrastructure to wallets & defi, with over 120 portfolios.

Passkeys... could bring the ultimate web3 experience.

Life journey of a key on Ethereum, you have to protect your key. If your intent to sign a transaction, hash transaction, sign the transaction, then broadcast. Node extracts public key from signature, compares address with senders address - if it's true they check the balance - the nonce prevents a replay. If it's valid it's includd in a block.

Private key is non-human readable/rememborable (32 bytes), seedphrases suck and are difficult to remember.

There are multiple ways to preserve the key,

e.g. MPC-combined splitted shares, MPC-TSS (threshold signing), secret sharing schemes - splitting the responsibility of preserving the keys and recovery to different parties - so it's safer than having one single key. When yo usign something they're combined together to be signed.

There's multi-sig, where multiple single keys come together to sign something. e.g. signature aggregation.

Whether it's one key or splitting key into shares, we need to preserve it.
 Different places to store keys:
  * HSM 
  * Secure Enclave
  * Local computer
  * Hardware wallet
  * Physically On paper

How can we access these key shares, it's authentication. Something we have (cellphone number etc), something we are (retina/fingerprint), something we know (e.g. password)

MetaMask uses local key on computer

Privy's solution:
 * Multiple ways - AWS, iCloud, other servers
 * Local computer / mobile
 * Hardware security module

What could be better?
 - No single point of failure
 - Use faceid / touchid, to access one single key on the secure enclave
 - You can easily forget something you know
 - You can easily have no access to something you have (e.g. your device gets lost)
 - But, you are who you are.

WebAuthN: 

 81% of hacks relate to password leaks
 could be yubikey, or other methods
 the authenticator creates the keypairs
 and the keypair never leaves the device
 you can use the public key and the signature to do the verification
 for security: phishing resistance, webauth happens locally, and never leaves the authenticator
 you never share secrets with the server, they only verify your signature
  - better experience because no password fatigue
  - no need to write down loads of passwords
  - webauthn is standard for better authentication experience


'Cloud-based WebAuthN'
- On devices, you use your biometric, to access to key encrypted by your secure enclave, and can be backed up with end-to-end encrypted icloud.
- Cross-device, using the icloud service
- It can't be cross-platform, what if I have android, or google?
- FaceID uses infrared which makes it complicated to steal your keys from your iCloud account.


There are divering use cases:
 - every day browsing
 - asset management 

Device-based WebAuthN:
 - It's not your operating system which generates the keys for you
 - secure enclave locally generates the public key
 - it never leaves the device, or is accessible to the OS
 - whenever you sign, it's signed in the secure enclave
 - the keys' never leaked to providers like iCloud
 - but you can't use it across devices

How can we achieve cross-device + cross-platform

 - Here web3 magic happens, with smart contract accounts
 - Instead of EOA, which is a single key, which can sign on-chain
 - If you lose your key you can never access the acocunt
 - but with a smart contract account, it's the entity that represents you on chain
 - and can have multiple authentication types
 - e.g. you can have multiple signers
   - like your android account (device based) 
   - your iPhone (cloud based?)
   - can use e.g. 2/3 or 2/2 multi-sig
 - but the private key on Ethereum is secp256k1
 - but the curve used by webauthn is the secp256r1 curve
 - https://eips.ethereum.org/EIPS/eip-7212
 - two types of verifying signatures on-chain
   - protocol level
   - or contract-level, ERC-4337
     - The userop is the transaction unit for 4337
     - the bundler aggregates the transactions and executes them
     - the verification is done by the smart contract
 - secp256r1 verification is 3x more expensive 
 - k1 adopted by bitcoin and ethereum
 - r1 is standardized in the NIST Suite B algorithms


Different verifier solutions:
 - Could use 'Turnkey TEE', which ensures noone can 

Another option is solidity verification (FCL's libs)

Hardware secury modules are known to be exploited more often? but if you look at the ZK projects they've been exploited more often due to new crypto.

One option is ZK verifier, Risc0 Bonsai: Bonfire wallet, & Aiom's halo2-ecc: Know Nothing Labs

4th one is Protocol solution: EIP-7212 

the 4th one - EIP-7212 is the cheapest overall, as proven by clave team experiments

rollups should implement EIP-7212, which should be the first RIP (rollup proposal).

The burger of Juicy Web3:

 Key Layer (WebAuthN)
 Account Layer: smart contract - multiple signers, multiple keys
 Verifier: r1-precompile on rollups / FCL / Risc0
 
Experience:
 easy auth - sign-in with faceid / fingerprint
 high security (anti-phishing, no need for password)
 easy recovery - assign new device or social recovery methods (guardians)
 flexibility: allows upgradable rules, e.g. threshold signing
 
What about MPC?
- A tricky one
- splitting responsibilty key signing to multiple keys
- can help with social recovery 



Question:
 - rpId, don't bind to domain names
 - which is a huge security trade-off
 - and allow the user to optionally start to bind
 - what if they accidentally bind on a phishing site

Remark:
 - We don't think using passkeys as a single authenticaiton method for an account isn't hte best idea
 - using a device bound could be secure
 - using a pass key uploaded to icloud is only as secure as icloud
 - could use an SMS confirmation, sim swaps etc.
 - don't want an ethereum account to be compromised by a single thing

Use: multiple device based authentication, we are suggesting multi-sig?

Could have a time-lock for recovery, and something will only be able to recover after a 7 day delay. if somebody steals it, you can lock it?

## Links

- [description](https://example.com)