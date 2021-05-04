# W3F Open Grant Proposal
* **Project Name:** Suter Shield Polkadot
* **Team Name:** Suterusu project
* **Payment Address:** 0x05a0ec975b3cfbf370eaee284fdf01eb1c99ba41

> ⚠️ *The combination of your GitHub account submitting the application and the payment address above will be your unique identifier during the program. Please keep them safe.*

## Project Overview :page_facing_up:

### Overview

Suterusu brings unprecedented privacy protection to any platform supporting smart contracts. Suterusu already provides privacy protection for several major blockchains and dapps, such as Ethereum, Binance Smart Chain (BSC) and, smartBCH. We have also received a grant from the NEAR community and will deploy Suter Shield on the NEAR blockchain. By deploying Suterusu Shield on the Polkadot platform, it will bring privacy-preserving payment functionality to all the dapps and users in the Polkadot ecosystem. 

### Project Details

Suterusu integrates a state-of-the-art trustless ZK-SNARK scheme with nearly constant size proofs (ZK-ConSNARK in short) and efficient proof generation/verification. Our [scheme](https://eprint.iacr.org/2021/540.pdf) reduces the proof size by around 20% and improves the proof generation and verification efficiency by an order of magnitude.

Based on our ZK-ConSNARK scheme, we propose the Suterusu protocol that allows a user to convert any token issued on the Polkadot network to its anonymized counterparts in the Suterusu protocol and then run the Suterusu transfer functionality to hide the transfer account identity and transferred amount. Our product Suterusu Shield is a user interface that would allow the users of the Polkadot network to invoke the private payment functionality provided by the Suterusu protocol.

Suterusu protocol has three technical modules: fund, transfer, and withdraw. The fund module will convert a token issued in the Polkadot network into its anonymized version, while the withdraw module will convert the anonymized token back to its native form. The transfer module is the one that enables the confidential transfer of the anonymized token. This process will guarantee the transaction amount confidentiality and anonymity for both the sender and receiver. For more concrete information regarding the technical details of our protocol, please refer to the following [medium article](https://medium.com/suterusu/an-introduction-to-the-suterusu-protocol-fe890bc49ead) and our [Eurocrypt 2021 paper](https://eprint.iacr.org/2021/540.pdf).  

Since we have already deploy Suter Shield on Ethereum and BSC, the final deliverable for this project would be the successful deployment of Suter Shield on the Polkadot network.

### Ecosystem Fit

Help us locate your project in the Polkadot/Substrate/Kusama landscape and what problems it tries to solve by answering each of these questions:

* Where and how does your project fit into the ecosystem?

Suterusu aims to become a universal privacy-preserving payment infrastructure for programmable money. Suter Shield will be integrated with the Polkadot ecosystem in a seamless manner. The substrate pallet we build can be invoked by any user and DeFi builder in the Polkadot ecosystem who are interested in protecting their payment privacy.   

* Who is your target audience (parachain/dapp/wallet/UI developers, designers, your own user base, some dapp's userbase, yourself)?

As Suter Shield will be deployed as a substrate pallet, any Polkadot user who cares about their payment privacy will be our target audience and have the access to our private payment functionalities. Since the launch of Suter Shield Ethereum and BSC, we have already accumulated over 4500 users and around 250 million USD transaction volume. Suter Shield will also introduce our current user base to the Polkadot ecosystem via the deployment of Suter Shield Polkadot. 

* What need(s) does your project meet?
* Are there any other projects similar to yours in the Substrate / Polkadot / Kusama ecosystem?
  * If so, how is your project different?
  * If not, are there similar projects in related ecosystems?

A similar project to Suterusu would be Manta network, which started out as a private DEX project for the Polkadot ecosystem. The main difference between Suterusu and Manta can be listed as follows: 

Since Manta network is focused on private DEX while Suter Shield aims to become a private payment infrastructure, we believe the target audiences our product serves are much broader than those of Manta network.

The implementation of Manta network is based on arkworks, which is an implementation of a zk-snark scheme. The problem with the zk-snark scheme is that it requires a trusted setup while our proposed zk-consnark scheme does not require a trusted setup. This means not only our scheme does not incur the troublesome of the setup ceremony, but our scheme is also more secure and transparent. 

Finally, Suter Shield is a universal layer-2 private payment protocol that is compatible with most smart contract platforms. It has already been deployed on Ethereum, BSC and smartBCH while Manta network remains a PoC product. Rapid deployment of Suter Shield on the Polkadot network will greatly facilitate the development of Polkadot's private payment infrastructure by leveraging Suterusu's existing user base and first-mover advantage. 

## Team :busts_in_silhouette:

### Team members

Dr. Huang Lin, the CTO of the Suterusu project. He is an applied cryptographer by training. He holds Ph.D. degrees in Applied cryptography and privacy-preserving distributed systems from Shanghai Jiao Tong University and the University of Florida, respectively. He worked as a postdoctoral researcher at the Swiss Federal Institute of Technology (EPFL), during which he published his first paper related to blockchain and cryptocurrency with colleagues from EPFL and Cornell IC3. He then served as an associate principal engineer in ASTRI, Hong Kong, where he was the PI of several blockchain projects supported with multi-million-HKD funds. He has published over 20 papers with 1407 citations on applied cryptography and information security.

Jingjing Zhang, Tech VP of Suterusu, previously leads FBG-X department in research cryptocurrency and blockchain projects, and before joining FBG, he works for ByteDance as algorithm engineer in Revenue Growth department. Prior to that, he worked in eBay and Uber in US. He graduated from Cornell with a master degree in computer science.

Richard Liu, CSO of the Suterusu, previously founding partner of FBG Capital since 2017, managed over 100m usd Cayman fund and brought in Sequoia, Bitmain, Polychain, Matrix, Alibaba co-founders as LP, invested Coinlist, Blockstack, Polkadot, Dfinity, CHZ. Before that over 6 years in China Renaissance led and participated over $2.5bn private placements and M&A. Graduated from Shanghai JiaoTong University,


### Contact

* **Contact Name:** Dr. Huang Lin
* **Contact Email:** huanglinepfl@gmail.com
* **Website:** https://suterusu.io/

### Legal Structure

* **Registered Address:** Address of your registered legal entity, if available. Please keep it in a single line. (e.g. High Street 1, London LK1 234, UK)
* **Registered Legal Entity:** Name of your registered legal entity, if available. (e.g. Duo Ltd.)

### Team's experience

We have already deployed Suter Shield on Ethereum, BSC and, smartBCH testnet. The deployments have received significant support from the community. The transaction volume of Suter Shield BSC (when we write this proposal) is $230,621,582 (221,075 in BNB and 95,473,878 in stable coin) and we have 3,166 total users and 10,526 total deposits. The transaction volume of Suter Shield Ethereum is $20,985,684 (32 in ETH and 20,893,982 in stable coin) and we have 1,321 total users and 1,295 total deposits. For the latest figures, please check the following links: [Suter Shield BSC stats](https://bscshield.suterusu.io/shield_stats), and [Suter Shield ETH stats](https://ethshield.suterusu.io/stats). In addition, we have received a grant from the NEAR community and will deploy Suter Shield on the NEAR blockchain too. 

### Team Code Repos

* https://github.com/suterusu-team

### Team LinkedIn Profiles

* Dr. Huang Lin https://www.linkedin.com/in/huang-lin-0b70b886/
* Richard Liu https://www.linkedin.com/in/fengliu23/

## Development Status :open_book:

If you've already started implementing your project or it is part of a larger repository, please provide a link and a description of the code here. In any case, please provide some documentation on the research and other work you have conducted before applying. This could be:


* academic publications relevant to the problem,
* Our core technical paper <Efficient Range Proofs with Transparent Setup
from Bounded Integer Commitments> has been accepted by Eurocrypt 2021 (https://eurocrypt.iacr.org/2021/acceptedpapers.php). It has also been published on Eprint: https://eprint.iacr.org/2021/540.pdf. 
* Many technical discussions can be found on my own medium account: https://lh-76196.medium.com/ and the official Suterusu medium account: https://medium.com/suterusu. You can also find the latest news on Suterusu from our twitter handles: @suterusu_io and @Suter78058619. 

* previous interface iterations, such as mock-ups and wireframes.
* You can find the list of our products such as Suter Shield and Suter bridge from the official website of our project: https://suterusu.io/ and the link of Suter Shield are: https://shield.suterusu.io/. 

## Development Roadmap :nut_and_bolt:

### Overview

* **Total Estimated Duration:** 2.5 months
* **Full-Time Equivalent (FTE):**  1.5 full-time engineers
* **Total Costs:** 25k USD

### Milestone 1 Implementation of Rust-based Substrate Modules for Suter Shield

The deliverable in this milestone will include a Rust-based Substrate Modules implementation of Suter Shield. Since the current implementation of Suter Shield contracts is written in Solidity. We will need to translate them into Rust. 

* **Estimated Duration:** 2 month
* **FTE:**  1
* **Costs:** 20,000 USD

| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article/Tutorial | We will publish an article/tutorial/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Substrate module: Suter Shield | Our current smart contracts are written in Solidity and will be translated into Rust. The final deliverable will include the Rust-based Substrate modules that provide the equivalent functionalities as the fund, transfer and withdraw contracts of the existing Suter Shield product. |  
| 2. | Benchmark | perform a unit test to ensure the security of the substrate modules and their compatibility with the Polkadot network. |  
| 5. | Docker | We will provide a docker file to demonstrate the usage of our modules |


### Milestone 2 Example — The deployment of Suter Shield Polkadot

The deliverable of this milestone will include UI and client-side algorithm modules which will enable the users to invoke all the aforementioned substrate modules. It will also include a working product that the Polkadot developers and users to run Suter Shield Polkadot to protect their payment privacy. 

* **Estimated Duration:** 0.5 month
* **FTE:**  0.5
* **Costs:** 5,000 USD


| Number | Deliverable | Specification |
| -----: | ----------- | ------------- |
| 0a. | License | Apache 2.0 / MIT / Unlicense |
| 0b. | Documentation | We will provide both inline documentation of the code and a basic tutorial that explains how a user can (for example) spin up one of our Substrate nodes. Once the node is up, it will be possible to send test transactions that will show how the new functionality works. |
| 0c. | Testing Guide | Core functions will be fully covered by unit tests to ensure functionality and robustness. In the guide, we will describe how to run these tests. |
| 0d. | Article/Tutorial | We will publish an article/tutorial/workshop that explains [...] (what was done/achieved as part of the grant). (Content, language and medium should reflect your target audience described above.)
| 1. | Deployment of Suter Shield Polkadot| We will provide the client-side algorithm modules mentioned in our [technical specification](https://medium.com/suterusu/an-introduction-to-the-suterusu-protocol-fe890bc49ead), such as CreateAddress, CreateFundTx, CreateTransferTx, and CreateBurnTx algorithms. We will also provide the necessary UI for the Polkadot users to use wallets such as Metamask to access the private payment functionality provided by the Suter Shield Polkadot. Deploy the new native smart contracts on the Polkadot network. We will have a working product that the Polkadot developers and users to run Suter Shield Polkadot to protect their payment privacy. |  
| 2. | Benchmark | perform a unit test to ensure the usability of Suter Shield Polkadot. |  
| 5. | Docker | We will engage both the Suterusu and Polkadot communities on the testing of Suter Shield Polkadot. |


