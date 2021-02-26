# 项目简介


ZKSwap 是一套基于自动化做市商（AMM，Automated Market Maker）的代币 Swap 协议。通过 ZK-Rollup 技术在 Layer-2 实现了 uniswap 的全套功能，同时提供无限可扩展性和隐私性。
ZKSwap 为流动性提供者和交易者提供超高吞吐量的 Swap 基础设施，且交易无需任何 Gas 费用。
	
## ZKswap的优势
目前大部分的去中心化交易所 DEX 例如 Uniswap，区别于火币、OKEx 等中心化交易所，其将做市商自动化，用既定算法替代人工报价，不仅去掉了中心化的撮合与清结算，还消除了交易中的做市商。因此，他们能为用户提供高安全性和隐秘性的交易。

但是，由于区块链技术的局限性以及公链自身出块时间长和确认速度慢等问题，去中心化交易所面临着吞吐量低下、处理速度缓慢和 gas 费用昂贵等痛点，这些痛点也直接导致了用户的整体交易体验不佳，使得去中心化交易所的交易体验无法媲美传统的中心化交易所。

而 ZKSwap 通过 ZK-Rollups 技术在 Layer 2 上实现了传统去中心化交易所的兑换逻辑，使所有的兑换在 Layer 2 上完成，在降低用户交易成本的同时保证了用户整体的交易体验。相比传统 DEX，ZKSwap 具有以下优势：

**零 Gas 费用** : 相较于传统Dex上每一次交易所需动辄几十美金的 Gas 费用（随着以太坊价格提升，Gas会越来越高），ZKSwap上发生在Layer2上的**每笔交易Gas费为0**，为用户节省了极大的交易成本；

**更高的 TPS （Transation Per Second）**: 受制于以太坊链上 TPS 的限制，Uniswap 等传统DEX每秒钟可以成交的交易次数和交易容量有明显的天花板。ZKSwap 通过 GPU 优化的方式，可以以免信任的方式，实现几百到几千的 TPS，在加入足够的机器支持扩容的情况下，**ZKSwap 的 TPS 理论上将达到 6,000 左右的数量级**；

**速度快（实时交易）**: ZKSwap上所有交易都迁移至 Layer 2 上发生 ，用户不再需要等待一个区块的确认时间，可实现实时交易。


## 白皮书文档

[白皮书](https://github.com/l2labs/zkswap-whitepaper/blob/master/zkswap_cn.pdf)

[经济白皮书](https://github.com/l2labs/zkswap-whitepaper/blob/master/zks_economy_whitepaper_cn.pdf)



