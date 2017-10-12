Understanding the Blockchain
==============================================================================

The underlying engine to all Cryptocurrency, as specified by Satoshi Nakamoto in the whitepaper "Bitcoin: A Peer-to-Peer Electronic Cash System", is the blockchain. The blockchain, at it's most basic level, is a public ledger of transactions for a given cryptocurrency, though it can be used for much more than that. Each transaction on the blockchain must be processed, entered into the ledger, and meet consensus standards before it is confirmed. Transactions are grouped into "blocks" and each block is a sequential piece of the blockchain and contains mathematical proof that it proceeds from the previous block. ARK uses a Delegated Proof of Stake consensus strategy, rather than a Proof of Work strategy, decreasing the need to re-hash calculations and the needed computing power to sustain the blockchain. This Delegated Proof of Stage strategy also ensures that improvements to the ARK ecosystem are democratically handled via the blockchain and Delegate system as explained in another section.

Technical Details of ARK's Blockchain
------------------------------------------------------------------------------

- 8-Second Block time
- 25 transactions per block
- Utilizes routing tables to reduce latency
- Constant block reward of 2 ARK per block
- Adds SmartBridge data field for custom use and bridging blockchains
- Utilizes two types of functional nodes to run the ARK Core
  - Relay nodes - Nodes with full API functionality, acting as a backend for the feature rich lite clients. Relay nodes do not collect any transaction fee and do not​ ​have​ ​the​ ​ability​ ​to​ ​Forge​ ​ARK​ ​Blocks.
  - Forging nodes - Nodes with reduced API functionality, decreasing the exposure to potential DDoS attacks on the ARK Platform. Forging nodes are able​ ​to​ ​Forge​ ​ARK​ ​and​ ​receive​ ​transaction​ ​fees.
- The ARK network usage scales up to the level of Major Credit Card networks through potential​ ​core​ ​upgrades,​ ​for​ ​example:
  - Increasing​ ​the​ ​number​ ​of​ ​Forging​ ​Delegates
  - Increasing​ ​the​ ​Block​ ​Size​ ​to​ ​include​ ​more​ ​transactions
  - Implementation of pre-approval PBFT block concept testnet [codename: TwinChain]  
  - Routing​ ​tables,​ ​to​ ​minimize​ ​hops​ ​among​ ​nodes​ ​when​ ​blocks​ ​are​ ​broadcast
  - Include​ ​forging​ ​with​ ​ARK​ ​Uncles