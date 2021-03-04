### 5 FREQUENTLY ASKED QUESTIONS

####1. Why does ZKSwap develop Uniswap in Layer 2 ？
Since 2019, the blockchain industry has undergone breathtaking changes. Decentralized finance(DeFi) continues to grow at an exponential rate. The Total Value Locked in different DeFi protocols has exceeded 70 billion U.S. dollars. With the continuous development of numerous on-chain assets and off-chain assets going on-chain, we believe that the Total Value Locked in DeFi protocols will soon exceed 100 billion U.S. dollars. These on-chain assets require fast, frictionless, trust-free, and real-time exchange services, which has led to the rise of new decentralized exchange(DEX) protocols such as Uniswap.

Although the new DEX model spearheaded by Uniswap has achieved significant development, it still has obvious drawbacks. First, the high gas fee of dozens of dollars per transaction hinders new users to entry; second, every transaction and every execution needs to wait for at least one block to confirm, which gives an unsatisfactory experience; and third, subject to the limiting TPS of Ethereum, Uniswap has a clear bottleneck in transaction numbers and transaction capacity per second. Those drawbacks are not unique on Uniswap. They are common issues faced by all DEXes.

ZKSwap (a ZK-Rollups based token Swap protocol) is a brand-new exchange protocol based on ZK-Rollups technology. Through Zk-Rollups technology, all ERC20 tokens are transferred through Layer2, and the consistent state of Layer1 and Layer2 is guaranteed based on continuously generated zero-knowledge proofs. This solution allows all transactions and swap to execute on Layer 2, achieving real-time swap with zero gas fees, unlimited scalability, removing the constraint from the Ethereum's TPS. The user no longer has to wait for the one-block confirmation time for each transaction. ZKSwap enables a DEX to provide the smooth user experience of a centralized exchange(CEX) while allowing the users to have full custody over their funds. We believe that ZKSwap is the future form of token trading platform. It will trigger a significant evolution of all existing DEX and CEX.

####2. Zkswap's advantages compared to Uniswap

Although new Dex such as Uniswap has made great progress, but there remains considerable amounts of shortcomings. ZKSwap's has the following advantages compared to Uniswap:

**0 Gas Fee** : Compared to dozens of dollars worth of Gas Fee resulted from transactions on tranditional Dex (Gas Fee will continue to increase as the price of Ethereum increases), ZKSwap transactions on Layer-2 requires zero Gas Fee，which greatly reduces transaction cost for users.


**High TPS（Transation Per Second）**: 
Hindered by TPS limitations on Ethereum, traditional Dex such as Uniswap has obvious bottleneck in transaction numbers and capacity per second. Through optimizing GPU, ZKSwap can conduct hundreds and thousands of TPS with trustless method. In the case of having enough machines to support expansion, ZKSwap's TPS can theoretically reach 6000.

**Real time transaction**: All transactions on ZKSwap are transfered to Layer-2 and are valid for real-time transction, users DO NOT need to wait for the one-block confirmation time.

####3. The difference between ZKSwap and Centralized Exchange (CEX)

Centralized crypto exchange, represented by exchanges such as Binance, Huobi, OKex, etc., has gathered a huge number of users and transactions. The main differences between ZKSwap and centralized exchanges are as follows:

**From the perspective of asset security**, CEX wallet stores and manages all users’ asset. Due to the large amount of funds, it is easy to attract hackers. Once a problem occur, almost all users will suffer losses; in ZKSwap, users’ Assets are not stored on the platform, but managed by smart contracts. During the transaction, the platform does not touch the user's assets. Each transaction requires users to complete the confirmation with a private key signature, and the swap of assets is directly transferred to the account L2 wallet.

**From the perspective of asset control**, in CEX, user assets are controlled by the platform, and users need to transfer their assets to the wallet of the trading platform. The asset custody function of the centralized trading platform is just like a bank. The user deposits the money in the bank, and the bank gives the user an account to record the user’s funds. The bank has absolute control over the user’s funds; on ZKSwap, the user’s assets are completely  in the control of the user. ZKSwap does not provide fund custody services, so it cannot control or transfer users' funds. As a decentralized exchange in Layer-2, ZKSwap has passed the security audits of three major audit institutions (ABDK, Certik, and SlowMist) for its contracts and circuit codes. Users control their own private keys and their assets are safe and controllable.


**From the user registration process**, in CEX, users register for an account and set a password to enter the exchange. This process generally requires KYC.  Corresponding materials need to be submitted to be reviewed. On ZKSwap, users can use ZKSwap without KYC by connecting the Ethereum wallet to the ZKSwap platform, making the process faster and more convenient.

**From the transaction process**, CEX transactions are completed through order book matching; ZKSwap uses automatic market maker AMM model, which has obvious advantages in user asset utilization efficiency and transaction depth. The transaction process is executed by the smart contract, without any third party acting as intermediary.

####4. Where is the user's funds entrusted?
The user's assets in ZKSwap Layer-2 are entrusted in the smart contract and are completely under their own control. Except for the user who owns the account private key, other third parties cannot control or transfer  the user ’s assets. Even if the project team stops the service, the users can still retrieve the assets autonomously from the smart contract.

####5. The difference between ZKSwap and Loopring Protocol

The main difference between ZKSwap and Loopring is areas of product route, technical details and user experience.

**In terms of product design**,Loopring is a Layer-2 DEX based on the order book model, and it has also begun to explore Layer-2 DEX based on the AMM model. ZKSwap mainly focuses on Layer-2 DEX based on the AMM model, and hopes to build more Layer-2 infrastructure in the future.

**In terms of technical details**,Loopring uses Groth16's zero-knowledge proof algorithm, and the circuit needs to be reset every time a trading pair is launched. ZKSwap is based on the newer Plonk zero-knowledge proof algorithm, which is more efficient and is capable of updating the trusted settings without having to update the circuit every time.

Overall, Layer 2 is a track with hugh opportunities, and Layer 2 projects are too few, not too many. We believe that more and more projects will enter this track in the future and bring more innovation and diversity into the ecosystem. ZKSwap hopes to build a complete Layer 2 ecosystem together with these projects.

####6. How to trade on ZKSwap
After the user connects the wallet to zks.app, deposits assets to the second-tier account of ZKSwap, he can then start trading. For the specific transaction process, please refer to: [ZKSwap Web app Tutorial](https://zks.app/docs/tutorial-en.pdf)


####7. Why can’t L2 transfers be directly transferred to the exchange's(Biannce, Huobi, etc.) address?
Since the exchange currently does not support ZKSwap Layer-2 transfer, users should not use the L-2 transfer function to transfer funds to the exchange address. In future, we will seek the L2 transfer cooperation with the exchange, and support users to transfer ERC20 tokens to the exchange address in real time through ZKSwap with 0 Gas fee.

####8. Can ZKSwap's withdrawal be faster?
The recent upgrade on ZKSwap Layer2 system  has optimized the ZKSwap withdrawal function. The withdrawal time from Layer 2 to Layer 1 processed by the smart contract on ZKSwap will be directly shortened from 30-60 minutes to 20-40 minutes.
In future, we will continue to optimize technology and iterative products to provide better service and experience to ZKSwap users.

####9. Why is there a minimum account balance requirement before L2 transfer and swap can be performed?

Since L2 transfers and transactions on ZKSwap need to generate zero-knowledge proofs and send them to Layer 1 to ensure asset security, and the data on-chain process will generate a certain amount of Gas fees. In order to limit the increase in ZKSwap operating costs caused by malicious  attacks, we limit the minimum balance of the account to reduce the risk of attack. Therefore, users need to deposit at least 50ZKS or the equivalent of 200 usdt tokens into the L2 account before performing L2 operations.

####10. Why did ZKSwap choose the ZK-Rollups technical route?

After a lot of research and testing, the ZKSwap project team found that ZK-Rollups is the best option for ETH scaling. ZK-Rollups adopts the popular Rollups expansion idea to realize the expansion of Layer-2. At the same time, ZK-Rollups uses zero-knowledge proof technology to upload calculation proofs on Layer-2 in real time, achieving almost the same level of security as Ethereum Layer-1 network.

ZK-Rollups has great advantage in finalizing transaction, and the withdrawal time has been significantly shortened, which greatly improves the user experience. In addition, with the upgrade of computer hardware and the development of zero-knowledge proof algorithms, the performance of Layer-2 can be further improved on the existing basis. Therefore, ZK-Rollups has achieved a good balance in terms of scalability, security, usability, and performance, and is currently the most suitable layer 2 solution for building DEX.

####11. What is the current TPS of ZKSwap? How to achieve scalability? Why is it said that due to the overall consensus of Ethereum, spending more money can not increase TPS?

Compared with Ethereum's 10-20 TPS, ZKSwap's current TPS is about 100 transactions in 15 seconds, and theoretically TPS can reach more than 6000. Because all transactions occur in Layer 2, ZKSwap has unlimited scalability. In future, ZKSwap will focus on the following areas to improve scalability:

1. **Expand a large number of prover nodes**
2. **Increase the chunk value of each block to increase the number of fast packaged transactions**
3. **Optimize the circuit design, optimize the GPU**

Ethereum's consensus has throughput limitations, and throughput depends on block size and block time. The larger the block, the shorter the block time and the greater the throughput.
However, larger blocks are not conducive to the decentralization of nodes, and reducing block time will increase the probability of chain forks. Simply increasing the block size or reducing the time between block generations cannot solve the problem, because the block needs time to transmit and verify. If the block is too large, it will cause increase the inconsistency of the network nodes (more forks) , which seriously affects safety.

####12. How to list tokens on ZKSwap?

In future, ZKSwap will open community governance. The community can propose to initiate a token listing application. Users who participate in ZKS's long-term PoS mining activities can vote on the token listing proposal with the gZKS obtained from the PoS mining activities.

####13. How does ZKSwap L2 account work?
At present, ZKswap's products including: layer2 wallet and Layer2 AMM swap protocol. The wallet is used to store and user's Layer 2 assets, while the AMM protocol is used to conduct swap and transactions. This is similar to the wallet + transaction function of a traditional centralized exchange. Layer 2 wallet and Layer2 AMM swap protocol are indispensable to complete the full Layer 2 transaction process. 


####14.How to transfer ETH and ERC20 through ZKSwap through web3 wallet? 
Currently ZKSwap supports Metamask, imToken, TokenPocket and Bitpie wallets to transfer ETH and ERC20 tokens through ZKSwap, and users do not need to pay any gas fees. Please download the wallet and set up the connection. After that, ZKSwap will continue to connect to more wallets for users to use. See the specific ZKSwap mainnet tutorial:

[ZKSwap App on Ethereum Mainnet Tutorial](https://zks.app/docs/tutorial-en.pdf)


####15. How does ZKSwap's system work?

The ZKSwap system consists of on-chain smart contracts, off-chain ZKSwap
server, the zero-knowledge proof system, and front-end user interface.

![ZKSwap System Archtecture](https://zks.org/images/blog/11/1.png)


**ZKSwap Smart Contract**

ZKSwap will deploy a series of smart contracts on
the Ethereum blockchain to store the tokens deposited by users while recording
and verifying Layer 2 status updates and related proof. Those smart contracts
are the key hub connecting on-chain and off-chain.


**ZKSwap Layer 2 Server**

The ZKSwap server is the module that processes all transactions off-chain. The ZKSwap server can use the WebSocket to interact with the user, and monitor transactions on the Ethereum blockchain. All valid transaction requests will be put into the ZKSwap mem pool and processed by the Swap Engine. The transaction types in the mem pool are the same as the transaction types of Uniswap. The Block Proposer will roll up the transactions and generate a new block. The State Keeper will update the status of all tokens on Layer 2. The State Keeper will send the state to the Commiter, which is responsible for communicating with the Prove Server, obtain the proof of the corresponding transaction, and finally send the state and the corresponding
SNARK proof via Ethereum sender to the ZKSwap smart contract on-chain.

**Plonk Zero-knowledge Proof System**

ZKSwap’s zero-knowledge proof system adopts a distributed architecture and uses the latest zero-knowledge proof
algorithm PLONK to generate proofs. The Prove Server supports multiple
Provers. Multiple Provers actively query the proof tasks in the Prove Server and send them back to the Prover Server after generating the proof. PLONK’s global trust setup only needs to be generated once, and the circuit can be greatly reused within a certain range, reducing the threshold for using zero-knowledge proofs.


**ZKSwap state tree**

The status tree of the ZKSwap system records the balance of all accounts in
the current system. The state tree of ZKSwap is a Merkel tree with a height of
34. The child nodes of the Root are all account nodes (24 levels) in the system.There are two types of account nodes:

* Ordinary account node: to record the status of all tokens in the account. Ordinary account nodes can have any number of leaf nodes (10 levels), each leaf node represents a type of token and its amount; there can’t be repeated token types within one account.

* Pair account node: to record the status of the liquidity pool of a certain pair of assets ZKSwap. The Pair Account Node contains only two leaf nodes. Each leaf node represents the balance and type of one token in the liquidity pool.

The transaction process in ZKSwap is essentially the process of updating the
state tree. The following section will be the introduction of all transaction types in ZKSwap and their corresponding State changes.


####16. What is the development plan of ZKSwap？

ZKSwap will actively cooperate with exchanges and crypto wallet service providers to support ZKSwap's Layer 2 standard, support ETH and all ERC20 free transfers (including stable coins, etc.), and support private transactions and private crypto swap.

ZKSwap is expected to complete the Plonk zero-knowledge proof system circuit optimization and the introduction of GPU acceleration by the end of 2021. In addition, the L2 Lab that supports the development of ZKSwap will continue to promote the development of the Layer 2 protocol layer. ZKSwap will further explore the application of Layer 2 in NFT, stablecoin and other fields, and introduce the EVM mechanism to build a standard Layer 2 protocol to support more DeFi projects use ZKSwap technology to build future DeFi applications on Layer 2 and create an open and complete Layer 2 DeFi ecosystem.


L2 Lab will also be committed to promoting the paradigm shift of the blockchain industry. By creating a Layer 2 protocol standard with an excellent user experience, Layer 1 will become the foundation of clearing and settlement, and Layer 2 will become the bridge connecting blockchain applications and Layer 3. And entrances and exits. The mission of ZKSwap is to allow all blockchain applications to run in a layer 3 world without any restrictions.

[ZKSwap Sets Out Roadmap for 2021](https://zkswapofficial.medium.com/zkswap-sets-out-roadmap-for-2021-1fb39be999b3)
