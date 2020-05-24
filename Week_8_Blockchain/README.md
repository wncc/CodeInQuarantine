# Week 8 | Blockchain 

## Introduction

First, it was "cloud computing," then "big data," followed by the "internet of things" and "artificial intelligence" - these are all buzzwords from technological paradigm shifts that eventually push the privacy management envelope, & the next buzzword, which is capable of impacting the technology stack of several domains including financial firms, consultants & healthcare providers is "blockchain". However, for many, the blockchain is still a nebulous concept. And even if they understand the “what”, understanding why it should be used and what problems it can solve remains unclear.

A blockchain is, in the simplest of terms, a time-stamped series of immutable records of data that is managed by a cluster of computers not owned by any single entity. Each of these blocks of data (i.e. block) is secured and bound to each other using cryptographic principles (i.e. chain). So, what is so special about it and why are we saying that it has industry-disrupting capabilities?

To understand this, head over to the resources & dive into the world of blockchain technology.

## Resources

-   ### [Introduction to Blockchain](https://www.wncc-iitb.org/wiki/index.php/Introduction_to_Blockchain)
    _Head here to understand the fundamental concepts behind blockchain technology & what makes it so popular_

-   ### [Smart Contract Development in Ethereum](https://www.wncc-iitb.org/wiki/index.php/Ethereum_Smart_Contracts_Tutorial)
    _A DApp (Decentralized Application) is similar to a traditional Web application, but communicates with a blockchain for data storage & retrieval. Since its inception, Ethereum has provided a large arena for a multitude of DApps to be built on top of it. The smart contract represents the core logic of a decentralized application because the business logic is represented by one or several smart contracts interacting with the underlying blockchain._
    
    _With this tutorial, we walk you through the process of setting up your development environment for Ethereum development and creating, testing & deploying your first smart contract on Ethereum._

- ### [DApp Development on Ethereum with Solidity & Web3](https://www.wncc-iitb.org/wiki/index.php/DApp_Development)
    _Once you are familiar with basic smart contract development, you can actually use them & build your very own decentralized applications (DApps). This is an article that talks about the essentials of Ethereum DApp Development, including Web3 & the libraries to use Web3, along with a curated list of tutorials to help you understand how to build DApps from scratch._

- ### Blockchain Beyond Ethereum
    _Although we have spoken a lot about Ethereum & development on it, blockchain is certainly not limited to Ethereum. There are tons of other chains out there with hundreds of awesome DApps built on them. Here, we provide you with some resources to understand about different blockchains & also get started with developing on them. We also have some resources for __crypto & math enthusiasts__ about stuff like Zero-Knowledge Proofs._

    - #### EOSIO
        - [Introduction to EOS [Part 1]](https://blockgeeks.com/guides/eos-beginners-guide-part-1/) [[Part 2]](https://blockgeeks.com/guides/what-is-eos-part-2/)
        - [Elemental Battles: Learn EOSIO by Building a Game](https://battles.eos.io/)
        - [EOSIO Developers Portal](https://developers.eos.io/welcome/latest/index)
        - [Comparison between EOS & Ethereum](https://blockgeeks.com/guides/ethereum-vs-eos-ultimate-comparison-guide/)

    - #### Tezos
        - [Beginner's Guide to Tezos](https://medium.com/@linda.xie/a-beginners-guide-to-tezos-c9618240183f)
        - [Tutorial: Building a DApp on Tezos](https://hackernoon.com/build-your-first-dapp-on-tezos-rwgl3ymb)
        - [Tezos Developer Documentation](https://tezos.gitlab.io/index.html)

    - #### Hyperledger Fabric
        - [What is Hyperledger?](https://blockgeeks.com/guides/hyperledger/)
        - [Guide to Setting up Hyperledger Fabric](https://medium.com/akeo-tech/step-by-step-guide-to-set-up-hyperledger-fabric-network-b80977c29b8a)
        - [Hyperledger Fabric Comprehensive Tutorial [Part 1]](https://blockgeeks.com/guides/hyperledger-fabric-tutorial-part-1) [[Part 2]](https://blockgeeks.com/guides/hyperledger-fabric-tutorial-2/) [[Part 3]](https://blockgeeks.com/guides/hyperledger-fabric-tutorial-part-3/)
        - [Official Fabric Documentation](https://hyperledger-fabric.readthedocs.io/en/release-2.0/)

    - #### Some Other Cryptocurreny & Blockchain Networks
        - [Quorum](https://blockgeeks.com/guides/quorum-a-blockchain-platform-for-the-enterprise/)
        - [Monero](https://blockgeeks.com/guides/monero/)
        - [ZCash](https://blockgeeks.com/guides/zcash/)
        - [Cardano](https://blockgeeks.com/guides/what-is-cardano/)
        - [AION Network](https://blockgeeks.com/guides/what-is-aion/)
        - [Cosmos Blockchain](https://blockgeeks.com/guides/cosmos-blockchain-guide/)

    - #### Zero-Knowledge Proofs
        - [Brief Introduction to Zero-Knowledge Proofs](https://towardsdatascience.com/what-are-zero-knowledge-proofs-7ef6aab955fc)
        - [zkSNARKs](https://z.cash/technology/zksnarks/)
        - [zkSTARKs [Part 1]](https://vitalik.ca/general/2017/11/09/starks_part_1.html) [[Part 2]](https://vitalik.ca/general/2017/11/22/starks_part_2.html) [[Part 3]](https://vitalik.ca/general/2018/07/21/starks_part_3.html)
        - [Bulletproofs](https://medium.com/coinmonks/zero-knowledge-proofs-using-bulletproofs-4a8e2579fc82)
        - [Zokrates: Zero-Knowledge on Ethereum](https://zokrates.github.io/)

- ### Build Your Own Blockchain
    - [Build a Javascript Blockchain [Part 1]](https://www.codementor.io/@savjee/how-to-build-a-blockchain-with-javascript-part-1-k7d373dtk) [[Part 2]](https://www.codementor.io/@savjee/implementing-proof-of-work-blockchain-in-javascript-part-2-k9ozymkqw)
    - [Creating  Minamist Blockchain using Python](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)
    - [Building a Blockchain in Golang (Video #18-27 in this Series)](https://www.youtube.com/watch?v=uCR_A-Bphl0&list=PLJbE2Yu2zumCe9cO3SIyragJ8pLmVv0z9)

## Tasks

1. ### Full-Fledged NFT
    In the [DApp Development on Ethereum with Solidity & Web3](https://www.wncc-iitb.org/wiki/index.php/DApp_Development) tutorial, we shared a tutorial to create a DApp & implement a basic custom ERC721 token. The tutorial only involves _minting_ these crypto-tokens. 

    This task intends to extend the DApp created in the above tutorial to include the full functionality of an ERC721 NFT (which includes transferring tokens, setting allowances, buring tokens, etc.). For this, you would have to go through the [specifications of ERC721 Token Standard](https://medium.com/crypto-currently/the-anatomy-of-erc721-e9db77abfc24). 

    The UI could should be modified to display the token owner as well with each token & have an interface for transferring these tokens.

    _Bonus: If you have a fair understaning of both ERC20 & ERC721, you could try and create a custom ERC20 token & bind it to your NFT to create a crypto marketplace for your NFTs. For this, you may need to add additional fields to the basic ERC721 token to include its cost in terms of the ERC20 token. Then, you would have to write a wrapper contract for the marketplace which basically uses the `transfer()` function from both tokens in a single transaction to conduct a transaction._

2. ### Incentivized Content Sharing Platform (Minimalistic Version)
    In this task, you are supposed to extend the ideas discussed in the ERC20 & IPFS-related tutorial respectively in order to create a platform where a user can upload documents to IPFS, store the hash on the blockchain & share the hash with other users [This may not be done on the platform directly]. Functionality should be there such that a reader can tip the content creator (or person sharing the file) with some ERC20 tokens (or ETH as well) if (s)he finds the content interesting.