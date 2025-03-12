---
layout: page
title: Get Started with Chia NFTs
permalink: /get-started-chia-nfts/

nav_exclude: true
---

# Get Started with Chia NFTs
{: .no_toc }

<a href="https://chialinks-com.translate.goog/get-started-chia-nfts/?_x_tr_sl=en&_x_tr_tl=zh-CN&_x_tr_hl=en&_x_tr_pto=wapp" class="btn"><img src="/assets/images/google-translate.png" width="15" /> Translate this page to another language</a>

NFTs (Non-Fungible Tokens) identify unique ownership of a digitized asset on a blockchain. Although NFT use cases go beyond digital art and media, their rise in popularity in 2021-2022 was primarily focused on digital art. There was an expectation that NFTs would create a new opportunity for digital artists and creators to be recognized and fairly compensated for their work in line with their counterparts in the physical art market.

However, early implementations of NFTs such as the popular [ERC-721](https://ethereum.org/en/developers/docs/standards/tokens/erc-721/) standard left a lot to be desired in fulfilling that promise to creators as well as providing true ownership to collectors.

The Chia team [recognized these shortcomings and developed the Chia NFT1 standard to address these](https://www.chia.net/2022/05/11/our-vision-for-chia-nfts/). Read on to find out how NFTs on Chia differ from NFTs on other chains and the advantages it offers both creators and collectors.

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
- TOC
{:toc}
</details>

## Chia NFTs for Creators

### Digital Identity and Provenance
Decentralized Identifier (DID) Profiles in Chia are a way for creators and collectors to identify themselves online. A DID can optionally be associated and verified with external linkages such as social media accounts and other real-world identifiers. **This allows creators to attach provenance to the history and origin of an NFT to distinguish authentic collections from copycats.**

### On-chain royalties
Royalties on secondary sales are one of the most attractive promises of NFTs to digital artists but on other chains this is enforced by centralized marketplaces that can (and have) changed their royalty enforcement policies at any time. **In Chia, the enforcement of royalties is embedded at the individual smart coin level** and are enforced on any sale using *Offer Files* and trusted wallets. Note that transfers (moving an NFT from one address to another without the exchange of another asset) do not have royalties enforced to allow users to organize their assets freely.

### Digital Permanence
NFT standards on other chains only allow the inclusion of a single location to store an image or asset -- usually this is an IPFS or Arweave link. If the asset changes location or the link is no longer available in the future, the NFT is essentially broken. **Chia NFT1 standard allows multiple redundant URIs** as well as the ability for the NFT owner to append additional URIs with matching data hash at any time to ensure better digital permanence. This extends to the metadata and license URIs as well.

### Marketplace Independence
*Chia Offer Files* are a trustless Peer-to-Peer mechanism to transact assets on the Chia blockchain without an intermediary party and with no counterparty risk. *Offer Files* also enforce royalties therefore there is no reliance on any middle parties (such as centralized marketplaces) to act as escrow. **Individuals can sell and trade their NFTs with others via any communication means** such as email, physical QR codes, social media, or [one of many DEXs and *Offer Files* discovery websites](https://chialinks.com/nfts/#marketplaces).


## Chia NFTs for Collectors

### True NFT ownership
In other chains that use an *account model*, NFT ownership is recorded in a smart contract which becomes a single point of failure. An exploited smart contract puts the entire collection at risk. With how the *coinset model* works in Chia, **each NFT is a separate smart coin and only the owner of that coin has the ability to spend it**.

### On-chain Provenance
Decentralized Identifier (DID) Profiles in Chia allow the association of a person to an NFT. This provenance of who created the NFT, who has owned the NFT in the past, and who currently owns the NFT is recorded on-chain and becomes part of the NFT itself. Imagine a house or a painting that was previously owned by a notable person or was part of an historic event -- that **provenance adds a rich story and potential value to the asset**.

### DID Collections
Collectors can create Decentralized Identifier (DID) Profiles to associate and organize NFTs they own. **This allows for a central place to showcase a collection to others** and allows others to contact the collector to make an offer.

### P2P Offers
*Chia Offer Files* allow collectors to **buy and sell NFTs peer-to-peer without any counterparty risk nor a central marketplace taking fees**. Collectors can create *Offer Files* to sell or bid on an NFT. This file can then be shared with [one of many DEXs and *Offer Files* discovery websites](https://chialinks.com/nfts/#marketplaces) with just a couple clicks. Many of these sites will propagate and share your *Offer File* with each other as well. Peer-to-peer trades can also be made between buyers and sellers without involving any marketplace by sharing an *Offer File* over any communication medium such as email, physical QR code, direct message, etc.

<!-- 
### On-chain Royalties
By ensuring that creators are paid royalties on secondary sales, 
NFTs that have royalties configured to fully or partially pay to a known charity introduces an unavoidable cost to wash trading. Collectors can have more confidence that the pricing of these collections are not the result of market manipulation. -->


## Useful Resources to Check Out
- [Dexie NFT Markets](https://dexie.space/nft) - Premier marketplace to discover NFTs for sale
- [FarmersMarket.cc](https://farmersmarket.cc/) - Rarity rankings and organized display of select NFT projects
- [Chia Friends Discord](https://discord.com/invite/ECAteZ2B6n) - Community run Discord for the Chia NFT community
- [MintGarden Top Collections](https://mintgarden.io/collections) - Listing of top NFT collections
- [MintGarden Studio](https://mintgarden.io/mint) - Easy-to-use minting tool for creators
- [SpaceScan.io Insights](https://www.spacescan.io/xch/insight/nft-volume) - NFT Volumes and other charts