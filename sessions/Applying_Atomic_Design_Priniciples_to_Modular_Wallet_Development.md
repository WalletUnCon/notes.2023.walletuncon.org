---
Title: Applying Atomic Design Priniciples to Modular Wallet Development	
Convener(s): Harish Raisinghani(https://github.com/harishraisinghani)
Scribe(s): Jay Pozo(https://github.com/jaypozo)
Links to any presentation matter: https://bit.ly/goldrush-kit-walletuncon
---

## Notes

- Atomic design is methodology for creating design systems. 
    - Consider Atomic Design as a mental model for UI design systems meant to be able to quickly shift between the abstract and the concrete
    - Can simultaneously see your interfaces broken down into their atomic elements and also how those atomic elements combine to form our experiences. 
- Design Stages:
    - 1: <b>Atoms</b> serve as the foundational building blocks that comprise all our user interfaces. Think of these as your component libraries.
    - 2: <b>Molecules</b> which are relatively simple groups of UI elements functioning together as a unit. They generally adhere to the single responsibility principle.
    - 3: <b>Organisms</b> are relatively complex UI components composed of groups of molecules and/or atoms and/or other organisms. These organisms form distinct sections of an interface
    - 4: <b>Templates</b> are page-level objects such as complete layouts and wireframes which include atoms, molecules, and organisms
    - 5: <b>Pages</b> which are specific instances of templates that show what a UI looks like with real representative content in place
    
## Demo using [GoldRush Kit](https://github.com/covalenthq/goldrush-kit)

React components for your dApp frontend. 200+ Chains. Open-source. Customizable. Designed to be an extension of your product. 

![organism_nft](https://hackmd.io/_uploads/S1FW5RVN6.png)
![organism_txn_table](https://hackmd.io/_uploads/r11m9044T.png)
![organism_multichain_balances](https://hackmd.io/_uploads/Sy3QoAEET.png)

![goldrush_themes](https://hackmd.io/_uploads/S1UO9CVVT.png)

## Links

- [GoldRush Kit](https://github.com/covalenthq/goldrush-kit)
- [Atomic Design](https://atomicdesign.bradfrost.com/)
