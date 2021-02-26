# 技术文档

## 1.零知识证明
证明者能够在不向验证者提供任何有用的信息的情况下，使验证者相信某个论断是正确的。零知识证明实质上是一种涉及两方或更多方的协议，即两方或更多方完成一项任务所需采取的一系列步骤。证明者向验证者证明并使其相信自己知道或拥有某一消息，但证明过程不能向验证者泄漏任何关于被证明消息的信息。据此，ZKSwap团队进行了详细解读。

[ZKSwap团队解读零知识证明PLONK电路](https://zks.org/zh/blog/12)

[ZKSwap团队解读零知识证明PLONK协议](https://zks.org/zh/blog/13)

[ZKSwap团队解读零知识证明算法之Bulletproofs：Range Proof 1](https://zks.org/zh/blog/14)

[ZKSwap团队解读零知识证明算法之Bulletproofs：Range Proof 2](https://zks.org/zh/blog/15)

[ZKSwap团队解读零知识证明算法之Bulletproofs --Range Proof 3](https://zks.org/zh/blog/16)

[ZKSwap团队解读零知识证明算法之Bulletproofs：Arithmetic Circuits](https://zks.org/zh/blog/18)

[ZKSwap团队解读零知识证明算法之Zk-stark（一）](https://zks.org/zh/blog/21)

[ZKSwap团队解读零知识证明算法之Zk-stark（二）——Arithmetization](https://zks.org/zh/blog/22)

[ZKSwap团队深入解读零知识证明算法之Zk-stark（三）：Low Degree Testing](https://zks.org/zh/blog/23)

[ZKSwap团队深入解读零知识证明算法之Zk-stark（四）——FRI协议](https://zks.org/zh/blog/24)



## 2.ZKSpeed

ZKSwap 的第一版扩容方案 ZKSpeed 基础架构结合了 ZK-rollup 和 Validium 和 Plasma 方案特点，在此基础上又通过聚合证明、GPU 优化、证明电路优化三个方案，大幅提升了整个网络的吞吐能力。详细介绍见：

[ZKSwap 提出实用 zk-rollup 协议 ZKSpeed，可大幅提升 Layer2 TPS 并降低 Gas 费用](https://zks.org/zh/blog/30)


## 3.ZKSwap design spec

首先感谢ZKSync，它为ERC20代币交易提供了ZK-Rollup的框架。ZKSwap是在Ethereum上使用ZK -Rollups并基于PLONK证明系统的L2代币交易协议。ZKSwap设计规范详细描述了ZKSwap协议以及与ZKSync的区别。

[ZKSwap开发设计规范](https://github.com/l2labs/zkswap-spec)
