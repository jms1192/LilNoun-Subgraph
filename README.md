# LilNoun-Subgraph
This subgraph offers an in-depth analysis, capturing both token transactions and governance delegation events within the Lil Nouns DAO. By visualizing these key activities, stakeholders can gain valuable insights into the organization's operational dynamics and governance structures.

#Overview
This subgraph is engineered for the lilnoun blockchain. It indexes and queries data using The Graph Protocol, focusing on various events emitted by the blockchain. This documentation aims to provide an in-depth view into each event handler, its purpose, and the parameters it records.

# lilnoun Subgraph Handlers

This repository contains handlers for the `lilnoun` subgraph. These handlers are written in TypeScript and are designed to interface with a blockchain.

## Event Handlers

Here is a list of event handlers and the data they process:

### ApprovalEvent

- `owner`: Address of the owner
- `approved`: Address of the approved entity
- `tokenId`: Token ID
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### ApprovalForAllEvent

- `owner`: Address of the owner
- `operator`: Address of the operator
- `approved`: Approval status
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### DelegateChangedEvent

- `delegator`: Address of the delegator
- `fromDelegate`: Previous delegate address
- `toDelegate`: New delegate address
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### DelegateVotesChangedEvent

- `delegate`: Delegate address
- `previousBalance`: Previous delegate balance
- `newBalance`: New delegate balance
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### DescriptorLockedEvent

- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### DescriptorUpdatedEvent

- `descriptor`: New descriptor
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### LilNoundersDAOUpdatedEvent

- `lilnoundersDAO`: Updated DAO address
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### MinterLockedEvent

- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### MinterUpdatedEvent

- `minter`: New minter address
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### NounBurnedEvent

- `tokenId`: Token ID that was burned
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### NounCreatedEvent

- `tokenId`: Token ID that was created
- `seed_background`: Seed for background
- `seed_body`: Seed for body
- `seed_accessory`: Seed for accessory
- `seed_head`: Seed for head
- `seed_glasses`: Seed for glasses
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### NounsDAOUpdatedEvent

- `nounsDAO`: Updated DAO address
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### OwnershipTransferredEvent

- `previousOwner`: Previous owner address
- `newOwner`: New owner address
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### SeederLockedEvent

- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### SeederUpdatedEvent

- `seeder`: New seeder address
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash

### TransferEvent

- `from`: Sender address
- `to`: Receiver address
- `tokenId`: Token ID
- `blockNumber`: Block number
- `blockTimestamp`: Block timestamp
- `transactionHash`: Transaction hash
