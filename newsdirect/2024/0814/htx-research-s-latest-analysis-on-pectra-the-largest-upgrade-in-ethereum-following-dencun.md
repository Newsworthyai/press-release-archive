# HTX Research's Latest Analysis on Pectra, the Largest Upgrade in Ethereum Following Dencun

Key Insights

● Key proposals in the Pectra upgrade (EIPs 7702, 3074, and 7623) will provide direct benefits to projects in the modular, chain abstraction, and AA wallet sectors.

● EIP-7594 (PeerDAS) introduces Data Availability Sampling (DAS), which is expected to be advantageous for ZK Prover networks and, by extension, the broader ZK field.

● Other minor EIPs are anticipated to lower L2 data layer costs, enhance transaction speeds, and reduce data storage costs.

● Given recent concerns about "high FDV, low liquidity," the upcoming Pectra upgrade in Q4 could potentially lead to a significant increase for the Ethereum ecosystem.

● The valuation of venture capital (VC) projects has become more reasonable amid the current "anti-VC" sentiment. Therefore, Q3 might offer a favorable window for institutional investors to enter the primary market, particularly in DeFi and innovative DeFi projects.

○ The price-to-sales ratios for DeFi projects have reached a historic low.

Background

Singapore / August 14, 2024 – The most discussed topic in the Ethereum community recently has been the Pectra upgrade. This upgrade combines two independent upgrades: Prague and Electra. Prague focuses on changes to the network's execution layer, while Electra impacts the consensus layer. Together, these upgrades are known as Pectra.

This event follows the Dencun upgrade in March 2024 and may become one of the most substantial upgrades in Ethereum's history.

According to Ethereum.org (https://eips.ethereum.org/EIPS/eip-7600), the Pectra upgrade is expected to incorporate several key Ethereum Improvement Proposals (EIPs) to address scalability, security, and user experience. These EIPs include:

EIP

1

EIP-2537

Precompile for BLS12-381 curve operations

Adds operation on BLS12-381 curve as a precompile in a set necessary to efficiently perform operations such as BLS signature verification

2

EIP-2935

Serve historical block hashes from state

Store and serve last 8192 block hashes as storage slots of a system contract to allow for stateless execution

3

EIP-6110

Supply validator deposits on chain

Provides validator deposits as a list of deposit operations added to the Execution Layer block

4

EIP-7002

Execution layer triggerable withdrawals

Allow validators to trigger exits and partial withdrawals via their execution layer (0x01) withdrawal credentials

5

EIP-7251

Increase the MAX_EFFECTIVE_BALANCE

Allow validators to have larger effective balances, while maintaining the 32 ETH lower bound.

6

EIP-7549

Move committee index outside Attestation

Move committee index outside of the signed Attestation message

7

EIP-7685

General purpose execution layer requests

A general purpose bus for sharing EL triggered requests with the CL

8

EIP-7702

Set EOA account code for one transaction

Add a new tx type that sets the code for an EOA during one transaction execution

9

EIP-7594

PeerDAS - Peer Data Availability Sampling

Introducing simple DAS utilizing gossip distribution and peer requests

10

EIP-7623

Increase calldata cost

Increase calldata cost to decrease the maximum block size

11

EOF-related EIPs

EIP-663: SWAPN, DUPN and EXCHANGE instructions

EIP-3540: EOF - EVM Object Format v1

EIP-3670: EOF - Code Validation

EIP-4200: EOF - Static relative jumps

EIP-4750: EOF - Functions

EIP-5450: EOF - Stack Validation

EIP-6206: EOF - JUMPF and non-returning functions

EIP-7069: Revamped CALL instructions

EIP-7480: EOF - Data section access instructions

EIP-7620: EOF Contract Creation

EIP-7698: EOF - Creation transaction

Pectra, set to launch in Q1 2025, is another step in Ethereum's strategic development. Below, we will walk through some key EIPs in the Pectra upgrade and discuss their potential impact.

Analysis of Key EIPs

*EIP-7702: A groundbreaking wallet technology for account abstraction (AA) to replace EIP-4337. EIP-7702 allows existing externally owned accounts (EOAs) to execute any smart contract code, potentially leading to the creation of feature-rich and user-friendly wallets. This could facilitate the development of complex applications.

● EIP-7702 is highly compatible with previous work on account abstraction under EIP-4337. Although AA wallet projects have already spent significant time developing unique features based on the EIP-4337 standard, these distinct advantages will no longer exist, as EOA wallets can now achieve similar functionalities. This change will bring AA wallets into direct competition with widely-used EOA wallets like MetaMask, possibly requiring AA wallet teams to reposition their products.

● Future EOA wallets will be able to offer new features such as transaction sponsorship for gas fees, batch account and transaction management, and more. These functionalities can be updated over time, making them user-friendly for Web2 users and DeFi transactions. This may lead to novel and complex applications that attract Web2 users, and present a series of opportunities.

History

1. AA adoption and compatibility have been low: The success of the AA market depends on the Ethereum ecosystem's adoption of EIP-4337. However, many DApps and Layer 2 solutions have yet to support it. The total number of smart contract wallets, estimated from the combined users of Gnosis Safe and Argent (the most popular products), is only around 150,000.

2. EIP-4337's technical solution lacks clarity: Although EIP-4337 defines contract interfaces for infrastructure components like Bundlers, Paymasters, and Signature Aggregators, Ethereum left several critical technical issues unsolved. These challenges require project teams to explore different technical implementations.

*EIP-3074: Proposed in October 2020 and included in the Pectra upgrade on April 12, 2024.

The main idea behind EIP-3074 is to delegate control of EOAs to smart contracts. This proposal allows any EOA to function like a smart contract wallet without needing to deploy a contract, enabling more complex transaction schemes such as gas sponsorship and batch transactions.

● So how does EIP-3074 turn existing EOAs into smart contracts? EIP-3074 introduces the AUTH and AUTHCALL opcodes, which together allow a smart contract to send transactions on behalf of an EOA. This makes it possible to perform multi-signature transactions, batch transactions, sponsored transactions, key recovery, and more accessible CeFi exchange deposits.

● Specifically, a user first signs a transaction offline, and then either the user or a gas sponsor sends it to the Invoker contract (a special intermediary contract), which uses AUTH and AUTHCALL to authenticate and execute each target contract. This setup allows smart contracts to take on greater management responsibilities, enabling various operations to be performed on behalf of users.

● Each EOA address can extend functionality by setting up an Invoker logic contract. Invokers are flexible and offer highly customizable transaction logic and permission control. They are closely associated with the intent-centric sector, where trading experience is optimized through the complex transactions incorporated in Invoker contracts. These include automated relaying transactions, conditional transactions, automated asset allocation, batch transaction aggregation, multi-signature transaction approval, time-limited transactions, integration with external systems, and specialized financial strategies. For example, a notable project ApertureFinance, which has handled transactions worth $2.6 billion, is popular among institutional traders. However, if the Invoker contract is compromised, it can lead to significant financial losses for users.

*EIP-7702: Proposed by Vitalik Buterin and built upon the core functionalities of EIP-3074

EIP-7702 allows EOAs to temporarily act as smart contract wallets during transactions, enabling EOAs to perform complex operations limited to smart contracts. This greatly enhances the functionality and flexibility of EOAs. Although this proposal operates at the protocol layer, it does not require permanent changes to the EVM when temporarily using the smart contract code, making it highly compatible.

Under EIP-7702, a smart contract code can be temporarily assigned to an EOA within a single transaction. This trustless approach ensures that any access or contract signature is removed after the transaction.

A smart contract's code is stored in "contract_code." Typically, the "contract_code" field is empty since EOAs are not contracts. However, during the transaction, this field is temporarily filled with a smart contract code.

EIP-7702 introduces a new transaction type that accepts both contract_code and signature fields. At the start of the transaction, the contract code from the signer's account is set as contract_code. At the end of the transaction, contract_code is reset to empty.

● EOAs can dynamically include smart contract codes during transactions, allowing them to execute multiple actions within a single transaction, such as batch processing and complex instructions. This simplification reduces transaction costs and operational complexity, making it particularly valuable for highly interactive financial applications like DeFi platforms.

● Additionally, EIP-7702 introduces a new permission management mechanism called "permission downgrading." This feature allows account holders to assign specific permissions to sub-keys, enhancing account security. Fine-grained permission control lets users limit the actions sub-keys can perform, preventing unauthorized transactions and misuse.

● EIP-7702 also includes transaction sponsorship, where one account can pay transaction fees on behalf of another. For instance, a service provider may cover costs for its customers, which simplifies user experience and potentially attracts more users.

● Currently, EIP-7702 has just been included in the Pectra upgrade, with details still unclear. However, given its significance as a key gateway in Web3—similar to how MetaMask and DeFi Summer enhance each other—this new Web2-friendly wallet solution could drive the development of new applications. Therefore, it merits close attention. At the same time, core DeFi applications such as Uniswap have also responded positively to EIP-7702.

EIP-7623: Proposed by Vitalik to increase calldata costs, reduce block size, and boost overall Layer 2 performance

Overview and background

● Since the implementation of EIP-1559, the block gas limit on Ethereum has remained constant. Meanwhile, as more rollups post data to Ethereum's calldata, the average block size has been steadily increasing.

● Calldata represents the data used for function calls in Ethereum smart contracts, including function selectors and parameters. While calldata is temporary and discarded after transaction execution to ease storage pressure, it still occupies block space and incurs gas fees.

● Following EIP-4844, rollup data are stored in blobs, which are now the preferred method for data availability (DA).

● This shift necessitates a reassessment of calldata pricing, particularly in addressing inefficiencies related to the average and maximum block sizes. The existing fee model and block size limits have failed to optimize calldata usage, leading to underutilized resources and higher costs.

● Ethereum's theoretical maximum block size is 1,875,000 bytes (1,831 KB), but the actual average size is only around 100 KB. This discrepancy is primarily due to the high gas fees associated with calldata, which reduce transaction volumes and leave block space underutilized, diminishing network efficiency and scalability.

● By introducing a calldata base fee for transactions primarily using Ethereum for DA, EIP-7623 reduces the maximum block size and frees up space for more blobs.

There is another related proposal:

● EIP-7706, introduced by Vitalik Buterin, aims to create a separate fee market for calldata, setting independent base fees and gas limits for further optimized transaction costs and network performance.

Overall impact

● Improved Ethereum Efficiency: The proposal aims to enhance transaction processing speeds and resource usage efficiency, preventing unnecessary cost increases and reducing calldata fees. This will help lower average transaction costs, better utilize network resources, and improve Ethereum's overall performance.

● Benefits for Layer 2s: The blob data design introduced in EIP-4844 complements this proposal. By aligning the base fee mechanism, Layer 2 solutions can more effectively use Layer 1 resources to boost overall Layer 2 and application performance.

● Advantages for Sequencers: Optimizing the fee structure for calldata and blob data can significantly lower the costs associated with data publication for sorters. Decentralized sequencers like Morph, Metis, Espresso, Eigenlayer, Astria, SUAVE, and Radius will benefit from these improvements.

EOF-related Upgrades

What Is EOF?

Ethereum Object Format (EOF) is a new standard introduced as part of the Pectra hard fork. EOF aims to improve how smart contracts are created and executed on the Ethereum network. By providing a more structured and efficient approach to managing smart contracts, EOF simplifies and secures the development process.

EOF introduces a new format for Ethereum smart contracts, making them easier to read and manage. This format helps reduce errors and enhance security by clearly defining the behavior of smart contracts. For developers, this means fewer bugs and vulnerabilities, resulting in more reliable applications on the Ethereum network.

EOF also improves the Ethereum Virtual Machine (EVM), the core component responsible for executing smart contracts. These enhancements make the EVM more efficient, enabling it to process more transactions simultaneously without slowing down. This is crucial for maintaining a responsive network as the number of users and applications grows.

Impact on the Pectra Upgrade

The inclusion of EOF in the Pectra hard fork enhances the upgrade's overall effect. By making smart contracts more secure and easier to develop, EOF ensures that new features introduced in Pectra—such as social recovery and transaction batching—can be implemented safely and efficiently.

EOF also supports the scalability improvements brought by Pectra. As the Ethereum network expands, it needs to process more transactions and run more smart contracts without sacrificing speed or security. The enhancements to the EVM and smart contract structure provided by EOF are key to achieving this goal.

Benefits for Developers and Users

For developers, EOF streamlines the process of creating and maintaining smart contracts. Clearer rules and better tools mean fewer errors and more robust applications. This, in turn, benefits users by providing more reliable and secure decentralized applications on the Ethereum network.

For users, the improvements brought by EOF result in a better overall experience. Faster transaction processing and more secure applications make Ethereum more appealing for everyday use. Whether for financial transactions, gaming, or other applications, users can enjoy a smoother and safer experience on the Ethereum network.

Overall, EOF is an integral part of the Pectra hard fork. It enhances the security and efficiency of smart contracts and supports the broader goals of the Pectra upgrade. By improving developer experience and ensuring better performance and security, EOF contributes to Ethereum's continued growth and innovation in the blockchain space.

EIP-7594-PeerDAS: Data Available Sampling (DAS) in the Pectra Upgrade

Protocol Overview

PeerDAS, also known as EIP-7594, implements DAS on Ethereum. This proposal is expected to considerably enhance the network's capacity to support rollups and their DA needs. Specifically, PeerDAS aims to increase the number of blob transactions that validators can attach to a block, from 3 to 64 or more per block.

PeerDAS is a notable enhancement in the Pectra upgrade, which is set to launch at the end of Q1 2025. PeerDAS addresses Ethereum's scalability challenges by ensuring data distribution and availability using existing peer-to-peer (P2P) components.

Key Features and Advantages of PeerDAS

1. Scalability and Efficiency: PeerDAS improves Ethereum's scalability by distributing the responsibility of DA across the network. Instead of relying on a few nodes to store and verify all data, it spreads the workload across multiple nodes, increasing overall network efficiency and resilience.

2. Improved DA: Using DAS, PeerDAS ensures that the data needed to verify transactions is accessible without overburdening any single node. This method involves checking a small, randomly selected subset of data to verify the availability of the entire dataset, reducing the strain on individual nodes.

3. Enhanced Network Resilience: By leveraging Ethereum'sbP2P components, PeerDAS strengthens the network's resistance to attacks and disruptions. This improvement in DA makes it harder for a single node of failure to compromise the entire network.

4. Integration with Other Upgrades: PeerDAS is part of the broader Pectra upgrade, which includes enhancements like EVM, EOF, and new EIPs such as EIP-7702. These upgrades collectively aim to optimize transaction processing, boost smart contract capabilities, and enhance user experience and security.

PeerDAS represents a crucial step toward improving Ethereum's scalability and resilience. By enhancing DA and leveraging Ethereum's decentralized network, PeerDAS lays the groundwork for a more robust and efficient blockchain ecosystem.

Two Advantages

Fostering DeFi development

● Increased Transaction Speed and Efficiency: PeerDAS enhances Ethereum's transaction speed and efficiency, allowing DeFi applications to process large volumes of transactions more quickly. This reduces wait times and improves user experience.

● Lower Transaction Costs: With increased network efficiency, PeerDAS helps reduce transaction costs, making DeFi projects more cost-effective and attractive to users.

Supporting emerging applications and innovations

● Expansion of Smart Contracts: The combination of PeerDAS with other improvements, such as EIP-7702, enables more flexible smart contracts, supporting innovative applications like decentralized identity verification and complex financial derivatives.

● Cross-Chain Interoperability: Enhanced data availability and network performance make Ethereum more capable of interacting with other blockchains, driving the development and innovation of cross-chain applications.

Benefit to ZK Prover Networks

Despite being powerful, zero-knowledge (ZK) technology faces challenges such as long zero-knowledge proof (ZKP) generation times and centralized Provers. Therefore, following ZK Rollups, ZKP generation hardware acceleration and decentralized Prover networks is becoming a trending sector in the primary market.

In this sector, companies like Succinct @SuccinctLabs and Cysic @cysic_xyz have raised $55 million and $12 million, respectively.

For instance, Cysic@cysic_xyz leverages its capability of designing ZK hardware acceleration chips to promote its ZK proving layer, Cysic Network.

As the market for ZKP generation services is still in its infancy, revenues are insufficient to cover Prover hardware depreciation, electricity costs, and operational maintenance. Therefore, ZK Prover networks often raise funds by issuing tokens and then reward Prover nodes through PoW to encourage adoption.

The Dencun upgrade catalyzed the emergence of several Layer 2 solutions with fully diluted valuations (FDVs) ranging from billions to tens of billions of dollars. Likewise, the Pectra upgrade is expected to ignite a new wave of ZK Prover networks with similar FDVs.

EIP-7251: Increasing the maximum effective balance and raising the validator staking cap from 32 ETH to 2,048 ETHProtocol Overview

EIP-7251, also known as "maxeb," is an enhancement proposed for the upcoming Ethereum Pectra hard fork. This change aims to mitigate the risk of instability in the beacon chain as the staked ETH approaches or exceeds 50% of the network's total.

Maxeb allows for the consolidation of multiple validators into fewer "super validators," streamlining operations without affecting monetary policy or rewards. It also benefits individual stakers by enabling them to accumulate rewards beyond the current 32 ETH limit.

However, there is division within the Ethereum community regarding the inclusion of maxeb in Pectra. The main concerns focus on its impact on network decentralization and validator diversity, with fears of potential centralization and reduced participation from smaller validators.

Proposal Motivation and Expected Impact

1. Reduced number of validators

With increased maximum effective balance, the total number of validators can be reduced, easing the network's load and improving efficiency.

2. Enhanced economic security

Raising the maximum effective balance can strengthen the network's economic security by preventing instability from a highly dispersed validator pool.

3. Lower operational costs

For large node operators, the proposal can reduce the need for multiple validators, lowering operational costs and maximizing rewards.

Ethereum developers have agreed to limit the staking ratio to 1/4, allowing individual validators to stake up to 2,048 ETH instead of the current cap of 32 ETH. Increasing the maximum effective validator balance enables operators to manage fewer but higher-staked validators, potentially simplifying operations.

Latest Developments● On June 27, 2024, Ethereum developers discussed and coordinated changes to Ethereum's consensus layer (CL, or the beacon chain). They explored new research on client diversity data collection and multi-client block validation.

● Pectra Devnet 1 is nearing readiness for release. The Ethereum Foundation's DevOps team is awaiting the readiness of the execution layer (EL) clients. Meanwhile, PeerDAS Devnet 1 has been launched, featuring implementations from three different CL clients.

Reference：https://eips.ethereum.org/EIPS/eip-7600

https://cryptomaniaks.com/ethereum-pectra-hard-fork-eof-cfi-prague-electra

https://github.com/ethereum/ercs/blob/master/ERCS/erc-4337.md?ref=blog.quicknode.com#backwards-compatibility

https://www.galaxy.com/insights/research/ethereum-all-core-developers-execution-call-187/

https://ethereum-magicians.org/t/eip-7623-increase-calldata-cost/18647

https://ethroadmap.com/?ref=bankless.ghost.io#pectra%20sticky （Etherum 升级Roadmap）

About Us

This article is a product of diligent work by the HTX Research Team that is currently under HTX Ventures. HTX Ventures, the global investment division of HTX, integrates investment, incubation, and research to identify the best and brightest teams worldwide. With more than decade-long history as an industry pioneer, HTX Ventures excels at identifying cutting-edge technologies and emerging business models within the sector. To foster growth within the blockchain ecosystem, we provide comprehensive support to projects, including financing, resources, and strategic advice.

HTX Ventures currently backs over 300 projects spanning multiple blockchain sectors, with select high-quality initiatives already trading on the HTX exchange. Furthermore, as one of the most active FOF (Fund of Funds) funds, HTX Ventures invests in 30 top global funds and collaborates with leading blockchain funds such as Polychain, Dragonfly, Bankless, Gitcoin, Figment, Nomad, Animoca, and Hack VC to jointly build a blockchain ecosystem.

Feel free to contact us for investment and collaboration at VC@htx-inc.com

Company Website

https://www.htx.com/ventures

About HTX Ventures

HTX Ventures, the global investment division of HTX, integrates investment, incubation, and research to identify the best and brightest teams worldwide.

With a decade-long history as an industry pioneer, HTX Ventures excels at identifying cutting-edge technologies and emerging business models within the sector. To foster growth within the blockchain ecosystem, we provide comprehensive support to projects, including financing, resources, and strategic advice.

HTX Ventures presently backs over 200 projects spanning multiple blockchain sectors, with select high-quality initiatives already trading on the HTX exchange. Furthermore, as one of the most vigorous Fund of Funds (FOF) investors, HTX Ventures collaboratively forges the blockchain ecosystem alongside premier global blockchain funds, including IVC, Shima, and Animoca.

Contact DetailsEE

glo-media@htx-inc.com

Company Websitehttps://www.htx.com/en-us/ventures

View source version on newsdirect.com: https://newsdirect.com/news/htx-researchs-latest-analysis-on-pectra-the-largest-upgrade-in-ethereum-following-dencun-171754607 

---

[Original/Source Press Release](https://newsdirect.com/news/htx-researchs-latest-analysis-on-pectra-the-largest-upgrade-in-ethereum-following-dencun-171754607)
                    

[Newsramp.com TLDR](None) 



[Reddit Post](https://www.reddit.com/r/BlockchainWeb3New/comments/1fvdnaw/pectra_upgrade_in_q4_key_proposals_and/) 



![Blockchain Registration](https://cdn.newsramp.app/news-direct/qrcode/248/14/waitb1Ln.webp)