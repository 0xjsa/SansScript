# Hackathon ETHGlobal Paris
## SansScript - Decentralized Newsletters Platform

![SansScript Logo](https://storage.googleapis.com/ethglobal-api-production/projects%2F89u46%2Fimages%2FScreenshot%202023-07-23%20at%2006.25.16.png)

## Prizes

Our project has been recognized and awarded in hackathon:

1. <img src="https://storage.googleapis.com/ethglobal-api-production/organizations%2F3zpxc%2Fimages%2Fapple-touch-icon%20(1).png" width="20" height="20"/> Worldcoin — Pool Prize
2. <img src="https://storage.googleapis.com/ethglobal-api-production/organizations%2Fpfyco%2Flogo%2F1663199654645_thegraph.jpeg" width="20" height="20"/> The Graph — Pool Prize
3. <img src="https://storage.googleapis.com/ethglobal-api-production/organizations%2F10a1v%2Flogo%2F1664802172170_aiOxYOJI_400x400.jpeg" width="20" height="20"/> Push Protocol — Pool Prize
4. <img src="https://storage.googleapis.com/ethglobal-api-production/organizations%2Fnbyyv%2Flogo%2F1664911830062_xmtp.png" width="20" height="20"/> XMTP — Prize Pool

## Project Description

SansScript is an innovative tool that merges web2 newsletter features with web3 capabilities, creating a decentralized and censorship-resistant platform for diverse newsletters. Users can easily create, publish, and subscribe to newsletters while benefiting from the power of web3 technology for content permanence on a decentralized network and direct payments to content creators without intermediaries. SansScript utilizes various protocols for certifications, messaging, notifications, data access and querying, storage, and payment solutions. Overall, the platform aims to provide a transparent, decentralized, and user-friendly ecosystem for newsletter creation, distribution, and monetization, empowering writers and embracing Web3 to unleash the potential of decentralized newsletters.

## How It's Made

SansScript employs multiple protocols to enable users to write, read, and subscribe to newsletters in a decentralized and censorship-resistant manner. Key technologies include:

- **@EAS Protocol**: SansScript uses attestations from the @EAS protocol to ensure the authenticity and validity of content.

- **@XMTP Protocol**: The platform sends messages using the @XMTP protocol, facilitating seamless communication between content creators and subscribers.

- **@Safe{Core} SDK**: Users can log in to the dApp using the @Safe{Core} SDK kits, providing options to sign in with an email or address and pay with FIAT or Crypto.

- **@The Graph**: The platform relies on @The Graph for indexing and querying data, ensuring efficient data retrieval and storage.

- **@IPFS**: SansScript stores images of newsletters using @IPFS, enabling content permanence and resilience.

- **@WorldCoin**: To ensure verified human participation, the project integrates @WorldCoin for user verification.

- **@ApeCoinDAO**: Users can pay in ApeCoin natively through @ApeCoinDAO, expanding the payment options available.

- **@Push Protocol**: SansScript leverages the @Push protocol to notify users when there is new content from the newsletters they have subscribed to.

Users can sign in to the dApp using two methods: the Metamask SDK or the Safe Sing-in Kit using Account Abstraction. Newsletter creators can verify with Worldcoin and then create a newsletter profile using a smart contract that indexes data in a new subgraph. Once the newsletter is created, readers can access the interface and subscribe to an existing newsletter. Users can subscribe to newsletters by paying with USDC and ApeCoin or using the on-ramp solution provided by Safe. When a creator writes a new newsletter, the protocol checks which addresses have active subscriptions and sends the message via Xmtp while notifying subscribers using the Push protocol.

