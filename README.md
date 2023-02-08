# Token Tooling

## Aptos NFT mint tool

The Aptos Non-Fungible Token (NFT) Minting Tool includes a CLI, a mint contract, and a template minting site that aim to lower the barriers for NFT creators to launch NFTs on Aptos. Currently, supported features include:

- Paying storage services with APTs. The Aptos NFT mint tool uploads NFT assets to Arweave through the [Bundlr](https://bundlr.network/) service. Bundlr makes it easy for creators to pay for the storage with APTs.
- Presale support through whitelisted addresses.
- Randomizing NFT mint order to reduce the impact of the rarity sniping tool.
- Supporting large-scale collections. The tool uploads assets in parallel and prepares the NFTs data in batches.
- Tracking progresses in a local DB

Aptos不可替代令牌(NFT)铸造工具包括一个CLI、一个铸造合约和一个模板铸造网站，旨在降低NFT创建者在Aptos上推出NFT的障碍。目前支持的特性包括:

—使用apt支付存储服务。Aptos NFT mint工具通过[Bundlr](https://bundlr.network/)服务将NFT资产上传到Arweave。Bundlr让创作者很容易通过apt支付存储费用。
-通过白名单地址提供预售支持。随机NFT铸币，以减少稀有狙击工具的影响。
——支持大规模收藏。该工具可以并行上传资产，批量准备nft数据。
—在本地DB中跟踪进度

hashlips_assets的文件需要先通过hashlip来生成images和json文件，然后才能使用该工具进行批量mint

For details about using the tool see: [https://aptos.dev/concepts/coin-and-token/nft-minting-tool/](https://aptos.dev/concepts/coin-and-token/nft-minting-tool/)
