# 文档结构

*阅读其它语言版本： [English](../table_of_contents.md)，[Korean](table_of_contents_KR.md)*

## MWC 详解

- [MWC 简介](intro.md) - MWC 技术介绍文档
- [致比特币持有者](MWC4bitcoiners_ZH-CN.md) - 从比特币的视角讲解 MWC

## 理解 MWC 部署

- [chain_sync](chain/chain_sync.md) - 关于 MWC 区块链如何同步
- [blocks_and_headers](chain/blocks_and_headers.md) - MWC 如何链上追踪区块和块头
- [contract_ideas](contract_ideas.md) - 部署合约的想法
- [dandelion/dandelion](dandelion/dandelion.md) - 关于交易生成和核销。生成枝干和扩散
- [dandelion/simulation](dandelion/simulation.md) - 蒲公英模拟 - 无需区块高度枝干和扩散即可聚合交易
- [internal/pool](internal/pool.md) - 交易池技术说明
- [merkle](merkle_ZH-CN.md) - MWC 偏好的默克尔树类型讲解
- [merkle_proof graph](merkle_proof/merkle_proof.png) - 应用修剪的默克尔树证明范例
- [pruning](pruning_ZH-CN.md) - 修剪技术说明
- [stratum](stratum.md) - MWC Stratum RPC 协议技术说明
- [transaction UML](https://github.com/mimblewimble/MWC-wallet/blob/master/doc/transaction/basic-transaction-wf.png) - 交互交易 UML （无需 `lock_height` 的聚合交易）

## 构建和使用

- [api](api/api.md) - 讲解 MWC 的 不同 API，及使用说明
- [构建](build_ZH-CN.md) - 讲解构建和运行 MWC 二进制软件
- [release](release_instruction.md) - 发行版本说明
- [usage](usage.md) - 如何在 Testnet3 使用 MWC
- [wallet](wallet/usage.md) - 讲解钱包设计和 `mwc-wallet` 次命令

## 其他  (wiki)

- [FAQ](https://github.com/mimblewimble/docs/wiki/FAQ) - 常见问题
- [构建 MWC](https://github.com/mimblewimble/docs/wiki/Building)
- [如何使用 MWC](https://github.com/mimblewimble/docs/wiki/How-to-use-MWC)
- [开发和贡献](https://github.com/mimblewimble/docs/wiki/Hacking-and-contributing)
