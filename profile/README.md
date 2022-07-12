# 👋 The Human File System Collective Superteam DAO 

🙋‍♀️ HumanFS DAO is a collective of separate HackFS teams cooperating to accelerating clinical discovery and reduce suffering. 

Together, we are creating a set of interoperable software libraries that can be used independently to create user-accesss controlled digital twins on the blockchain.
The libaries can be used independently, but will all be included in the HumanFS SDK. 

## :sunglasses: HumanFS SDK :sunglasses:
A Simple API for a Decentralized Health Data Sharing Protocol 

There are 350k health apps containing various types of symptom and factor data.  However, the isolated data's relatively useless in all these silos. In order to make clinical discoveries, all the factor data needs to be combined with the outcome data.  The web2 solution to combining all this data is a nightmare of
1. creating thousands of OAuth2 data connectors 
2. running a bunch of importer cron jobs on AWS.

**Web3 Solution**: User auth/databases/key management/access control/3rd party OAuth tokens abstracted away by a single, easy-to-use API

i.e. 

Pain Tracking App A:

 `db.collections.create('Arthritis Severity', timeSeriesData);`

Diet-Tracking App B:  

`let timeSeriesData = db.collections.get('Arthritis Severity');`

⇒ Making it possible for Diet-Tracking App B (and/or Pain Tracking App A) to easily analyze the relationship between dietary factors and Arthritis Severity using causal inference predictive model control recurrent neural networks.

## 🌈 Get Involved!

Are you or your team working on some aspect of this? 
Then join us on [Discord](https://discord.gg/TCrQDsRF) so we can coordinate and avoid duplication of effort.

👨‍🏫 You can also contribute to a task on [DeWork](https://app.dework.xyz/hackfs-dhealth-colle)

## 👩‍💻 Useful resources 

- 🤚 [Aragon DAO and Multisig](https://client.aragon.org/?#/humanfs/)
- 💬 [Community on Discord](https://discord.gg/TCrQDsRF)
- 🌎 [EthGlobal HackFS Project](https://ethglobal.com/showcase/human-file-system-mq03o)
- 👨‍🏫 [Tasks on DeWork](https://app.dework.xyz/hackfs-dhealth-colle)

## 🧙 Libaries Used

Fluence to perform decentralized analysis of human generated data from applications and backends on peer-to-peer networks. 

The Proof of Attendance Protocol for Sybil Resistant data collection, ensuring that robots aren't selling fake health data. 

XMTP (Extensible Message Transport Protocol) is an open protocol and network for secure, private messaging between patients and physicians.

Lit Programmable Key Pairs (PKPs) for access control over protected health information (PHI).

Valist to reward public good open-source health technology innovations using Software License NFTs and proof of open-source contribution.

Tableland for querying the HumanFS for specific data types and time periods.

NFTPort for minting data sets that can be sold to pharmaceutical companies in a health data marketplace.

Covalent for Health Data NFT marketplaces, On-Chain Analytics / Dashboards, Health Data Wallets, Health Data Asset tracking, and ROI for NFT generation and sales.
