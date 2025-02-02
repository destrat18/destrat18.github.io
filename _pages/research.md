---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /research
---
My research interests lie at the intersection of Formal Methods and Parametrized Algorithms within the context of blockchain technology.

## Smart Contracts
Smart contracts are programs that run on blockchains and currently manage billions of dollars worth of digital assets. You may have heard of tokens, NFTs, and stablecoins, which are typically controlled by smart contracts. These contracts play a significant role in our economy because they offer properties that traditional banking cannot, such as:

* **Trustless**: No central authority is required to enforce the terms of the contract.
* **Self-executing**: Their logic cannot be tampered with once deployed.
* **Transparent**: Everyone can view the code, data, and executions.

## Challenges of Smart Contracts
Smart contracts are not without flaws. They can have bugs, vulnerabilities, and inefficiencies. Some of the challenges I am interested in include:

* **Cost**: Executing smart contracts is expensive, as users must pay for computation and storage. Since every node in the network must execute each smart contract and store the data, the costs are high. In 2023 alone, users spent nearly 4 billion USD on execution fees on Ethereum.

* **Correctness**: Once deployed, smart contracts are immutable. Ensuring their correctness before deployment is crucial, as fixes are rare and costly. Vulnerabilities can be extremely expensive for the community. For example, the infamous DAO attack in 2016 resulted in an attacker stealing 50 million dollars due to a vulnerability in the contract code.

* **Scalability**: As the number of transactions increases, the network can become congested, leading to slower transaction times and higher fees. Finding ways to scale smart contracts efficiently is a significant challenge.

## Program Verification
Ensuring the correctness of smart contracts is crucial. Traditional testing methods fall short as they only cover a limited set of possible executions. To guarantee that smart contracts behave as intended in all scenarios, we need formal verification. Formal methods offer a mathematical approach to prove the correctness of smart contracts, providing a higher level of assurance that they are free from bugs and vulnerabilities.

