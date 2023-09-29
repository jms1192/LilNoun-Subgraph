# LilNoun-Subgraph

The lilnoun subgraph serves as a comprehensive analytical tool that utilizes The Graph Protocol to index and query crucial data from the lilnoun DAO. It captures a wide range of events, including token transactions and governance delegation activities within the Lil Nouns DAO, offering stakeholders an invaluable lens through which to understand the organization's operational dynamics and governance structures. 

This documentation outlines each event handler in detail, specifying the parameters it records, to provide a thorough understanding of the subgraph's capabilities and purpose. By seamlessly integrating these functionalities, the subgraph not only offers detailed visibility into individual transactions but also broadens the scope for data-driven decision-making within the DAO.

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
