# PHBS_BlockChain_2018
## Distributed Intelligent Production Network using blockchain technology, DIPNET
### 1、Introduction
Distributed Intelligent Production Network, DIPNET is a smart contract platform for industrial manufacturing, providing complete implementation of the underlying protocol, supporting tools, API interface sets, etc. This technology has major three advantages:
(1) Safe: The traditional industrial SaaS platform uses a firewall to prevent security. As long as the hacker breaks through the firewall, it can arbitrarily control the database stored centrally at the back end. The industrial blockchain forms the core of the protocol layer through consensus algorithm, cryptographic signature, distributed storage, etc., and cross-organization data mutual trust in production is completed through the blockchain, all order information, operation information and historical affairs, etc. Recorded in the alliance chain, the flood control modification of distributed ledgers will greatly increase the difficulty of hackers. It is also possible to create a virtual world of "digital twins" for each physical world's industrial assets and to confirm and transfer them. On the basis of ensuring the security of asset data, improve the operability of digital assets and provide protection for customized industrial APPs.
(2) Efficient: The traditional industrial Internet is supported by centralized cloud services, large-scale server clusters, and network equipment. When the number of people and devices connected to the network grows at billions of levels, the amount of traffic and cost to be processed between them is extremely alarming. In the distributed intelligent production network, both the end user and the terminal producer are connected as equal nodes, the data can be transmitted point-to-point between any nodes, and the information is interacted in real time, realizing the data of R&D, design, production, manufacturing and sales. . The transaction process is automatically executed by the targeted smart contract paradigm. An order confirmation by the end user triggers a rapid response of the entire industry chain, which can automate the data flow and promote the transformation and upgrading of the manufacturing industry.
(3) Decentralized: In the traditional networking mode, communication between all devices must be realized through a centralized proxy communication mode. The connections between devices must pass through the network, which greatly increases the networking cost, and is scalable, maintainable, and Poor stability. At the same time, there are diversified ownership among different production units, and the diversity of cloud service architectures supported by them makes communication between them very difficult. Blockchain technology uses P2P networking technology and hybrid communication protocols to handle communication between heterogeneous devices, significantly reducing the cost of building and maintaining a centralized data center, while dispersing computing and storage requirements into the various components of the IoT network. In the device, it effectively prevents the failure of any single node in the network, which causes the entire network to crash. The blockchain technology is used to set up and manage the industrial Internet of Things. 
### 2、Basic infrastructure
The industrial blockchain uses the mother-child double-chain model: the DPOS main chain and the DAG sub-chain. Different consensus schemes are used for different production links in the industrial manufacturing sector, taking into account reliability and performance. The infrastructure consists of the application layer, interface layer, contract layer, basic service layer, and network layer.
(1) The network layer mainly implements basic node discovery and data transmission. Ethereum's devp2p protocol has been implemented in the Ethereum network for many years, and its privacy, robustness, performance and other aspects have been well verified.
(2) The basic service layer mainly implements functions such as transaction data, block generation, and maintenance consensus. The industrial blockchain adopts the chained block structure of DPOS consensus. Later, as the number of transactions increases, it finally supports DAG implementation, and transfers data unrelated to payment to the DAG sub-chain, and provides underlying support for large-scale IOT data. The industrial blockchain uses the ECDSA-secp256k1 digital signature scheme. There are three types of accounts in the industrial blockchain: general accounts, contract paradigm accounts, and contract instance accounts. The common account is controlled by the user's private key, and the contract paradigm account and the contract instance account are all generated by a specific algorithm. The block service layer accepts the parameters passed in the upper layer, and can construct a specific type of transaction data. After the signature of the transaction sender, the transaction broadcast is realized through the network layer. For the DPOS main chain and DAG sub-chain transactions, the industrial blockchain will use different verification strategies. It is worth noting that the DAG subchain does not have the concept of a block.
(3) The contract layer mainly implements functions such as transaction data, block generation, and maintenance consensus. The industrial blockchain implements smart contracts through VMs. All contract paradigms and contract instantiation transactions are only allowed to be submitted in the main chain to guarantee the timing and reliability of smart contracts. The contract paradigm is submitted by the developer, and the smart contract instance is initialized by the user through the contract paradigm. Smart contracts can directly access data in the DAG subchain. The contract layer is the core link to realize the industrial blockchain business. The fulfillment of order intentions and order delivery are automatically performed by smart contracts.
(4) The interface layer mainly implements external interface functions such as block data access and smart contract interaction. The interface layer provides users and Dapp with access to the underlying block data, industrial blockchain accounts, smart contracts, contract paradigms, and is the primary means of interacting with industrial blockchain services.
### 3、Application scenery
(1) First is a one-click repeat customization. In the Internet era, the manufacturing industry has gradually turned to meet the consumer fragmentation demand and mass customization as the core production mode. The development of the production service industry has gradually become a new trend of manufacturing transformation and development. In this realistic context, the industrial blockchain advocates that the production of enterprises is not a simple copy, but a value creation in meeting the individual needs of consumers.
(2) The second is the value of life cycle management. The distributed manufacturing model formed by the distributed intelligent production network is represented by the user-created content, which enables everyone to manufacture and participate in the whole life cycle of the product, completely subverting the traditional manufacturing mode, and the production enterprise can also benefit.
(3) The third is the standardization and networking of infinite interaction. Data can be transmitted point-to-point between any nodes, and information can be exchanged in real time to realize data access in R&D, design, production, manufacturing, and sales. Order information, transaction history records, etc. are recorded on the chain, distributed storage can not be falsified, decentralized collaboration can be achieved, and product traceability is safe and convenient. The trading process is automated by smart contracts to increase efficiency.
### 4、Challenges
(1) Consensus: From the perspective of the public chain, the consensus algorithm is the choice of fairness and efficiency. Proponents of various consensus algorithms have thus formed different blockchain ecosystems, like various public chains, alliance chains, and private chains.
(2) Privacy: Personal privacy protection is a strong demand, but at the same time, the regulator must be made aware of the transaction content, otherwise it will get out of control. Privacy security is a double-edged sword that technically meets the need for privacy protection, but it also increases the complexity of system implementation.
(3) Expandability: The scalability problem is how to store the non-tamperable blockchain data as efficiently as possible, mainly focusing on two directions: a. Moving some transactions from the transaction layer to the sub-blockchain; b. starting from reducing storage.
### 5、Advice to policy maker
(1) Technology innovation: Forming a development consortium combining production, education and research;
(2) Serve the real economy: Cultivate industry leaders, leading companies and industrial ecology;
(3) Improve industry impact: Promote the construction of public service platform for industrial blockchain by leveraging the advantages of industrial alliances;
(4) Improve policy environment: Accelerate the development of relevant laws and regulations for blockchain and protect corporate intellectual property rights.
### Reference
[1] 徐强.(2018). 深化制造业数字化变革，探索建设工业区块链. [J].智能制造(10), 20-23.
[2] 李祥利. (2017). 区块链瞄准工业互联网，两把刷子解决互信机制. [J]. 今日制造与升级(3), 19-21.
