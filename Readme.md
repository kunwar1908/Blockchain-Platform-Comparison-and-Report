# Blockchain Platform Comparison and Report

## Comparison Table

| **Blockchain Name** | **Type**     | **Consensus Mechanism Used**        | **Permission Model** | **Speed / Throughput**      | **Smart Contract Support** | **Token Support** | **Typical Use Case**                   | **Notable Technical Feature**         |
|---------------------|--------------|-------------------------------------|-----------------------|-----------------------------|-----------------------------|-------------------|----------------------------------------|----------------------------------------|
| Ethereum            | Public       | Proof of Stake (Casper)             | Open                  | 15–30 TPS (Ethereum Mainnet) | Yes (Solidity)              | Yes (ETH)         | Decentralized Applications (DApps)     | Smart Contract Platform                |
| Hyperledger Fabric  | Private      | Pluggable (e.g., Raft, Kafka)       | Permissioned          | 1000+ TPS                   | Yes (Go, JavaScript)        | No Native Token   | Enterprise Supply Chains               | Channel-based Privacy                  |
| R3 Corda            | Consortium   | Notary-based (can be pluggable)     | Permissioned          | 170+ TPS (setup-dependent)  | Yes (JVM Languages)         | No Native Token   | Inter-bank Financial Transactions      | Point-to-Point Communication           |

## Short Report

Ethereum, Hyperledger Fabric, and R3 Corda represent different blockchain paradigms. **Ethereum** is a public blockchain using **Proof of Stake**, offering decentralized, open participation but lower throughput (~30 TPS). It supports smart contracts in **Solidity** and has a native token (**ETH**), making it ideal for DApps.

**Hyperledger Fabric** is a private blockchain with **pluggable consensus** and high throughput (1000+ TPS). It supports smart contracts in **Go/JavaScript** but has no native token. Its **permissioned model** and privacy via **channels** suit enterprise use cases like **supply chain networks**.

**R3 Corda**, a consortium blockchain, emphasizes privacy and scalability. It uses a **notary mechanism** instead of traditional consensus and allows smart contracts in **JVM languages**. With no native token, it suits **financial applications** among known entities.

- For a **decentralized app**, Ethereum is best due to its open nature and smart contract ecosystem.  
- For a **supply chain among known partners**, Hyperledger Fabric provides speed and privacy.  
- For **inter-bank applications**, R3 Corda is optimal, offering secure, permissioned, point-to-point data sharing.
