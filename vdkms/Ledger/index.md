---
title: Ledger 
layout: default
nav_order: 1
# has_children: true
---

# Ledger

Welcome to the Ledger section! Here you can learn more about the ledger, indy node, DID and different type of DIDs as well as the different txns.

### Overview

Ledger is a prominent blockchain technology company known for its hardware cryptocurrency wallets, but it's important to note that Ledger itself is not a blockchain. Rather, Ledger provides secure storage solutions for various cryptocurrencies that operate on different blockchains. The company's primary focus is on creating hardware wallets that allow users to securely store their private keys offline, protecting their digital assets from online threats. These devices support a wide range of cryptocurrencies and tokens, enabling users to manage multiple blockchain-based assets in one place. While Ledger doesn't operate its own blockchain, it plays a crucial role in the broader blockchain ecosystem by providing secure storage solutions for users interacting with various blockchain networks.

### Indy Node

The Indy Node is a key component of the Hyperledger Indy project, which is an open-source distributed ledger technology focused on decentralized identity. An Indy Node serves as a validator in the Indy network, participating in the consensus process to maintain the integrity and consistency of the distributed ledger. These nodes are responsible for processing transactions, validating new entries, and ensuring that the network remains secure and transparent.

Indy Nodes play a crucial role in managing decentralized identifiers (DIDs) and verifiable credentials within the Indy ecosystem. They store and manage the public elements of identity records, such as public keys and service endpoints, while ensuring that private information remains off-ledger. This approach allows for a robust, privacy-preserving identity infrastructure where individuals have greater control over their personal data. Indy Nodes work together in a permissioned network, typically operated by trusted institutions or organizations, to provide a reliable and scalable foundation for self-sovereign identity solutions across various industries and use cases.


### DIDs

Decentralized Identifiers (DIDs) are a type of globally unique identifier designed to enable individuals and organizations to have more control over their digital identities. There are various DID methods, each specifying how DIDs are created, resolved, updated, and deactivated on different systems. Some common DID methods include did:web, did:key, did:ethr, and did:ion. Each method has its own characteristics and is often associated with specific blockchain or distributed ledger technologies.

Two closely related DID methods are did:sov and did:indy. The did:sov method, which stands for "Sovrin," was one of the earlier DID methods developed for use with the Sovrin network, a public permissioned blockchain for self-sovereign identity. Did:indy, on the other hand, is a more generalized method designed for use with any Hyperledger Indy-based ledger, including but not limited to Sovrin. Both methods share similar structures and functionalities, as they are built on Indy technology. They allow for the creation of decentralized identifiers that can be resolved to DID documents containing public keys and service endpoints, enabling secure and verifiable interactions in decentralized identity ecosystems. The main difference lies in their scope: did:sov is specific to the Sovrin network, while did:indy can be used across various Indy-powered networks, offering greater flexibility for different identity implementations.

### Ledger Browser

The Ledger Browser allows a user to see the status of the nodes of a network and browse/search/filter the Ledger Transactions.
With the Ledger Browser, you can see:
  - The status of the Ledger nodes
  - The domain ledger's of an Indy Network - all identity-related operations (such as creating DIDs, writing schemas, credential definitions, etc.) are recorded.

  ![Screenshot of ledger]({{ site.baseurl }}/assets/images/ledger.png)


### Transactions

Transactions (txns) in Hyperledger Indy-based networks are fundamental operations that write data to the ledger. These transactions are crucial for establishing and managing decentralized identities and verifiable credentials. Key transaction types include:

  - DID (Decentralized Identifier) transactions: These write new DIDs to the ledger or update existing ones. DIDs serve as unique identifiers for entities in the network.
  - Schema transactions: These define the structure of credentials by specifying the attributes they will contain. Schemas are reusable and can be referenced by multiple credential definitions.
  - Credential Definition transactions: These create definitions that reference a schema and include the issuer's public key. Credential definitions enable the issuance of verifiable credentials based on a specific schema.

Other important transaction types include Node transactions for managing validator nodes, Attrib transactions for adding attributes to DIDs, and Revocation Registry transactions for managing credential revocation. Each transaction type plays a specific role in building and maintaining the decentralized identity infrastructure. For example, an organization might first write its DID to the ledger, then create a schema for a type of credential it wants to issue, and finally publish a credential definition based on that schema. This sequence of transactions sets the stage for the organization to issue verifiable credentials that can be trusted and verified by others in the network.


![Screenshot of txn]({{ site.baseurl }}/assets/images/txn.png)


### Conclusion

In conclusion, the landscape of decentralized identity and verifiable credentials is rapidly evolving, with technologies like Hyperledger Indy and DID playing pivotal roles. These systems work together to create a more secure, transparent, and efficient digital ecosystem for managing identities and credentials. By leveraging blockchain technology and cryptographic principles, they enable individuals and organizations to have greater control over their data while facilitating trusted interactions. As adoption grows and standards continue to develop, we can expect to see more widespread implementation of these technologies across various sectors, potentially transforming how we handle identity verification, credential issuance, and data sharing in both public and private domains. The ongoing development and integration of these systems promise to address longstanding challenges in digital identity management, paving the way for more secure, privacy-preserving, and user-centric digital experiences.
