Awesome Liquid
===============
A curated list of Liquid sidechain services and tools 
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

List of content:
- [Official releases](#official-releases)
- [Guide](#guide)
- [Explorer and statistics](#explorer-and-statistics)
- [Faucet and demos](#faucet-and-demos)
- [Blockstream's Asset Registry](#blockstream's-asset-registry)
- [Liquid Securities](#liquid-securities)
- [Tools](#tools)
- [Libraries](#libraries)

# Official releases
- [GitHub sources & Binaries](https://github.com/ElementsProject/elements/releases)

# Guide
- [Official website](https://blockstream.com/liquid/)
- [Technical overview](https://docs.blockstream.com/liquid/technical_overview.html)
- [Whitepaper](https://blockstream.com/assets/downloads/strong-federations.pdf)
- [Getting started with the Liquid Network](https://hackernoon.com/getting-started-with-the-liquid-network-c87e2cb5996b)
- [Labelling assets](https://medium.com/@gabriele.domenichini/liquid-daemon-3-14-1-23-and-labels-8ad1c06bb93e)
- [Hardware node](https://liquid.beer/pub)
- [Elements asset tutorial](https://github.com/ElementsProject/elements/tree/master/contrib/assets_tutorial)
- [Liquid: A Hands-On Introduction](https://docsend.com/view/gdxtzsz) at Consensus 2019 and [examples code](https://github.com/Blockstream/liquid-walkthrough)
- [Liquid Introduction Webinar](https://www.youtube.com/watch?v=C0bXBA6naMs) on YouTube
- [Liquid Multisig Issuance](https://github.com/Blockstream/liquid_multisig_issuance)
- [Asset tutorial](https://docs.blockstream.com/liquid/developer-guide/developer-guide-index.html#proof-of-issuance-blockstream-s-liquid-asset-registry)

# Explorer and statistics
- [Official statistics](https://liquid.net/)
- Official [Blockstream explorer](https://blockstream.info/liquid/)
- R based open-source [statistics page](http://vaccaro.tech:3838/liquid/)
- Liquid Sidechain Statistics at [Liquid.horse](https://liquid.horse/)
- List of [issued assets](https://gnet.me/liquid/)

# Faucet and demos
- Faucet to get L-BTC, USDt and LCAD in Testnet [faucet.vulpem.com](https://faucet.vulpem.com)
- Demo assets at [liquid.beer](https://liquid.beer/)
- MTL Coffee Token [montrealcoffee website - not working](https://montrealcoffee.club)
- [Buy Liquid BTC via Lightning - not working](https://liquid.beer/liquidity)
- [Liquid Testnet](https://liquidtestnet.com/) [sourcecode](https://github.com/valerio-vaccaro/liquidtestnet.com)

# Blockstream's Asset Registry
- [Asset Registry in JSON](https://assets.blockstream.info/)
- [Testnet Asset Registry in JSON](https://assets-testnet.blockstream.info/)
- [Human readable asset list](https://blockstream.info/liquid/assets)
- [Testnet Human readable asset list](https://blockstream.info/liquidtestnet/assets)

# Blockstream AMP (ex Liquid Securities)
- [Official website](https://blockstream.com/amp/)
- [Technical overview](https://docs.blockstream.com/blockstream-amp/overview.html)
- [Video introduction](https://www.youtube.com/watch?v=hTfd1LI1fs0)
- Open source demo faucet/authorizer at [liquid.wine](https://liquid.wine) and [sourcecode](https://github.com/valerio-vaccaro/liquid.wine)
- [External authorizer demo](https://github.com/valerio-vaccaro/LiquidSecuritiesAuthorizer)
- [Rust based AMP External Authorizer](https://github.com/valerio-vaccaro/amp-authorizer)
- [LiquidSecuritiesPOS](https://github.com/valerio-vaccaro/LiquidSecuritiesPOS) M5stack based POS for Blockstream AMP tokens.

# Tools
- [Liquid.Coach](https://vulpemventures.github.io/liquid.coach) Liquid.Coach lets you create and manage Elements transactions in the browser.
- [Liquid.Taxi](https://liquid.taxi) Pay Liquid network fees with USDt and other stablecoins
- [LiquiDEX](https://github.com/RCasatta/LiquiDEX) A decentralized exchange for Liquid transactions.
- [TDEX](https://tdex.network/)
- [Hal](https://github.com/stevenroose/hal/) with [hal-elements extension](https://github.com/stevenroose/hal-elements): tool to decode/create liquid transactions.
- [Liquid-melt](https://github.com/Blockstream/liquid-melt) allow to import collectible tokens from the Mini Private Key.
- [Nigiri](https://github.com/vulpemventures/nigiri) docker box.
- [Liquid swap](https://github.com/Blockstream/liquid-swap/) tool.
- [WriteOnChain](https://gitlab.com/valerio-vaccaro/writeonchain) write information on Liquid using OP_RETURN.
- [LiquidIssuer](https://gitlab.com/valerio-vaccaro/liquidissuer) Issue token on Blockstream Liquid sidechain compatible with Blockstream asset registry from a Python/Qt5 app.
- [Asset Registry Contract Calculator](https://github.com/valerio-vaccaro/asset_registry_contract_calculator) minimal gui for creation of an asset registry contract.
- [Jade](https://github.com/Blockstream/Jade) hardware wallet.
 
# Libraries
## C
- [Libwally-core](https://github.com/ElementsProject/libwally-core): C/C++ with bindings for Python2/3, Java and JavaScript (and [examples in python](https://github.com/afilini/wally-examples))

## Rust
- [Rust-elements](https://github.com/ElementsProject/rust-elements): liquid compatible blockchain data structures
- [Rust-liquid-rpc](https://github.com/stevenroose/rust-liquid-rpc): rust RPC interface for `liquidd`

## Go
- [go-elements](https://github.com/vulpemventures/go-elements) Go support for Liquid/Elements transactions 

## Javascript
- [liquidjs-lib](https://github.com/provable-things/liquidjs-lib)

## Python
- [python-elementstx](https://github.com/Simplexum/python-elementstx) (and [examples](https://github.com/Simplexum/python-elementstx/tree/master/examples))

## License

MIT License.

To the extent possible under law, [Valerio Vaccaro](https://github.com/valerio-vaccaro/) has waived all copyright and related or neighboring rights to this work.
