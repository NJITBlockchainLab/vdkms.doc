---
title: Mediator
layout: default
has_children: false
permalink: /mediator
---

# Mediator

Welcome to the Mediator section! Here you can learn more about the mediator, its importance in DIDComm communication and how it works.

### Overview

Mediators in DIDComm are routing agents that recipients specify for senders to use when transmitting messages. They act as intermediaries in the communication process, adding layers of privacy and routing flexibility. Mediators receive encrypted messages from senders and forward them to the intended recipients. Each mediator in the communication chain requires an additional layer of encryption, which the sender applies before transmission. This design allows for complex routing scenarios while maintaining end-to-end message privacy. Mediators are particularly crucial for mobile wallets, as they enable indirect message delivery to devices that cannot receive direct communications.

### Importance of Mediators

Mediators play a critical role in the DIDComm ecosystem, serving as essential intermediaries that enable secure and flexible communication between agents. They are particularly vital for mobile wallets, which cannot receive direct messages due to the limitations of mobile operating systems. By acting as designated routing agents, mediators allow senders to transmit messages to recipients indirectly, ensuring that even devices with restricted connectivity can participate in decentralized identity communications. This capability is fundamental to the widespread adoption and practical implementation of DIDComm in mobile environments.

Beyond their role in mobile communications, mediators significantly enhance the privacy and security of DIDComm interactions. They obfuscate the true endpoints of communication, making it difficult for outside observers to correlate messages across different relationships. Mediators also provide entities with the flexibility to use separate paths for sending and receiving messages, further improving privacy. Additionally, they support complex routing scenarios while maintaining end-to-end message privacy through layered encryption. This versatility allows organizations to implement sophisticated communication architectures, such as using gateway mediators to centralize external communications and simplify internal agent management, thereby enhancing both security and operational efficiency in decentralized identity systems.

### Working of Mediator

**1. HTTP Out Of Band Invitation**

   - This refers to the initial invitation process where the vehicle agent establishes a connection with the mediator through the out of band invitation. This step enhances security by ensuring the initial handshake happens through HTTP.

**2. Mediation established**

   - Once the out-of-band invitation is accepted, a mediated connection is set up between the vehicle agent (the app) and the mediator. This mediation allows for secure, standardized communication between the two entities. The mediator can facilitate data exchange and manage the ongoing connection between the vehicle agent and other parts of the system.

![Mediator Working]({{ site.baseurl }}/assets/images/mediator.png)

**3. WSS Protocol for Mobile-to-Mediator Communication**

   - Mobile agents use WebSocket Secure (WSS) protocol to communicate with their mediators. WSS provides a full-duplex, real-time communication channel that's encrypted, ensuring security for the initial leg of the message journey.
   - Before sending, the mobile agent encrypts the message or proof request. This end-to-end encryption ensures that even if intercepted, the message remains unreadable to unauthorized parties.

**4. Mediator-to-Mediator Communication**

   - Once a mediator receives an encrypted message from its associated mobile agent, it needs to relay this to the recipient's mediator. This inter-mediator communication uses the HTTPS protocol, adding another layer of transport security. It's worth noting that in some cases, both mobile agents might be using the same mediator, simplifying this step.

**5. Final Delivery to Recipient**

   - The receiving mediator then uses WSS to securely transmit the still-encrypted message to the recipient mobile agent. The recipient mobile agent decrypts the message, completing the secure transmission process.


![Mediator Working]({{ site.baseurl }}/assets/images/mediator_1.png)

### Conclusion 

This elaborate system ensures that communications remain secure and private, leveraging the benefits of both WSS and HTTPS protocols, end-to-end encryption, and the mediator model to create a robust and flexible communication framework.

### Notes

- **Non-Mobile Agent Communication**:
   - For agents that aren't mobile (e.g., web-based or server applications), the process is slightly different.
   - These agents communicate with the mediator using HTTPS rather than WSS. The mediator acts as a central hub, facilitating communication between these HTTP-based agents and other agents in the network.

- **Maintaining Security**:

   - Throughout this process, the original encryption of the message remains intact.
   - The mediators handle routing of encrypted data without needing to decrypt the actual content. This end-to-end encryption ensures that only the intended recipient can read the message, maintaining confidentiality even if a mediator is compromised.
