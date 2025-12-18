## Solidity 学习项目总览（task）

当前 `task` 目录下包含四个主要子项目，每个项目聚焦一个学习方向：

- **`begging/` 乞讨合约示例（Foundry）**  
  一个使用 Foundry 搭建的简单智能合约项目，包含 `BeggingContract` 合约及其部署脚本，用来练习基础合约编写、部署与调用流程。

- **`nftAuction/` NFT 拍卖与预言机项目**  
  完整的 NFT 拍卖系统，包括：拍卖合约、支持 ETH/ERC20 出价、Chainlink 价格预言机、价格库合约、UUPS 与透明代理可升级合约、部署脚本以及详细的文档说明，是当前的核心实践项目。

- **`NFT/` MyNFT721 铸造项目（Foundry）**  
  使用 OpenZeppelin 的 ERC721 标准实现的 NFT 合约 `MyNFT721`，配套有 Foundry 的部署脚本和 `broadcast` 记录，用于学习 NFT 的铸造、转账与基础元数据配置。

- **`ERC20/` MyErc20 代币项目**  
  一个简单的 ERC20 代币合约示例 `MyErc20.sol`，用于练习自定义代币的发行、转账与基本代币逻辑。


