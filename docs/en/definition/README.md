##Encyclopedia

###1.Definition

L1: Short for Layer-1, generally considered as the main chain of Ethereum.

L2: Short for Layer-2, it is a capacity expansion solution based on the Ethereum main chain.

L2 deposit: Transfer the token from Layer-1 account to ZKSwap Layer-2 account.

L2 Withdrawal: Retrieve the token from Layer-2 account and send it to Layer-1 account.

L2 transfer: Complete the transfer of token on Layer-2 without gas fees.

TPS: The number of transactions that can be processed per second.

ZKSwap: Layer2 token swap protocol based on ZK-Rollups.

ZK-Rollups: ZK-Rollups is a popular Layer 2 scaling solution. Its basic idea is to scale the network by aggregating multiple transactions and verify the proof on-chain. ZK-Rollups analyzes and verifies these aggregated transactions through smart contracts, and uses zero-knowledge proof technology to put the proof of aggregated transactions on-chain, thereby reducing the data that needs to be stored on-chain. All funds are locked in the smart contract, and most of the calculations and storage are done off-chain.

Zero-knowledge proof: The prover can convince the verifier that a certain assertion is correct without providing any useful information to the verifier. Zero-knowledge proof is essentially an agreement involving two or more parties, which is a series of steps that two or more parties need to take to complete a task. The prover proves to the verifier and makes him believe that the prover knows or possesses a certain message, but the certification process cannot be leaked to the verifier.

Uniswap： is an automated liquidity protocol powered by a constant product formula and implemented in a system of non-upgradeable smart contracts on the Ethereum blockchain. Users can create a liquidity pool by providing a certain percentage of ETH and any other ERC20 asset. One liquidity pool reserves ERC20 tokens and provides liquidity for the transactions between these two assets. In return, all liquidity providers will split the 0.3% of the transaction volume as a liquidity provider fee. In Uniswap, the first liquidity provider needs to set the ratio of the two assets in the liquidity pool. The automated market maker algorithm will ensure that the product of the two assets before and after each transaction remains constant.  

Create a Liquidity Pool： In Uniswap, each trading pair has only one liquidity pool, which is generally created by the first liquidity provider. For example, a liquidity provider creates an ETH-ZKS liquidity pool, and then adds liquidity. The initial amount of ETH deposited is x0, the number of ZKS stored is y0, and x0 ∗ y0 = c0. Here ZKS can be any ERC-20 token.

Liquidity Token：Liquidity Provider (hereinafter referred to as LP) will obtain the Liquidity Provider Token, (hereinafter referred to as LP Token or LT), which is used to represent the share of LP in the current liquidity pool. LP Token is an ERC-20 token that can be transferred without removing the liquidity of the liquidity pool. Each liquidity pool has a corresponding LP Token.

Create Liquidity：When adding liquidity to an existing pool, users must add pair tokens proportional to the current ratio.

Remove Liquidity： Liquidity provider can remove liquidity by burning their LP Token in the liquidity pool contract and retrieve the corresponding shares of two tokens from the pool.

Swap： After the liquidity pool is created and liquidity is injected, users who hold ETH or ZKS can start swapping in the liquidity pool.





###2.Layer 2 Concept Introduction

DeFi and NFT applications on Ethereum provide numerous revenue opportunities for the market, but as cost increases, the industry has begun to turn its attention to retail investors. As DeFi projects become more active, the load of contemporary protocols is very limited. Therefore, many Layer 2 protocols have emerged. The main goal of these protocols is to reduce the number of transactions on the Ethereum blockchain by transferring transaction activities to other places, while still using the main chain as a guarantee of security. For example, **state channels, side chains, Plasma, and Rollup**. The core idea of all Layer 2 solutions is to allow multiple participants to interact securely in some way, without the need to publish transactions on the main chain (ie Layer 1), but to a certain extent, the Ethereum network is still used as arbitration to ensure safety. Different Layer 2 solutions have different characteristics and advantages and disadvantages. 

The following articles elaborate on the current mainstream Ethereum layer 2 scaling solutions.

[Making Sense of Ethereum’s Layer 2 Scaling Solutions: State Channels, Plasma, and Truebit](https://medium.com/l4-media/making-sense-of-ethereums-layer-2-scaling-solutions-state-channels-plasma-and-truebit-22cb40dcc2f4)

[Overview of Layer 2 approaches: Plasma, State Channels, Side Chains, Roll Ups](https://nearprotocol.com/blog/layer-2/)

[Optimistic vs. ZK Rollup: Deep Dive](https://medium.com/matter-labs/optimistic-vs-zk-rollup-deep-dive-ea141e71e075)
