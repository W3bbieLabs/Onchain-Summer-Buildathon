`Date last modified: 2024 06 29`

# Public Good Club / Onchain-Summer-Buildathon

[Public Goods Club](https://publicgoods.club), courtesy of [W3BBIE](https://w3bbie.xyz). Built during [Base's](https://www.base.org/) [Onchain Summer Buildathon](https://www.base.org/onchainsummer?utm_source=dotorg&utm_campaign=onchainsummer).

_Welcome to the Public Goods Club README. Here, you will find a guide to context, design, and development._

---

## General Context

Public Goods are elements which everyone can access and enjoy — clean air, parks, public art, and free software. Also, Base’s tech makes it easy to build apps twhich onboard the next billion users onchain. Our community will be the comfy couch where regens worldwide land when they finally make the leap. And we love Onchain Summer!

### 🔗 Key Links Within The Public Goods Club World

- [Blue Paper](https://mirror.xyz/bigtrav.eth/_GeVdMm8DSEIS36EwbqlGCljoddrVgvK69kq62uRCHc)
- [PGC Website](https://publicgoods.club/)
- [Membership Mint](https://pgc-members.xyz/)
- [Member Token Bound Account (ERC-6551)](https://pg-club.netlify.app/)
- [Collectibles Gallery](https://zora.co/collect/base:0xa6735cb18ea3e233c535dacd7276d64db02fd9e3)
- [@PublicGoodsClub (X)](https://twitter.com/PublicGoodsClub)
- [@publicgoodsclub (Instagram)](https://www.instagram.com/publicgoodsclub)

### 💡 Why we Created Public Goods Club

We're a community of public goods enthusiasts and our mission is simple: to fund badass public goods projects. Public Goods Club is working from this epiphany: the coolest projects were funding public goods. Think Pizza DAO – turning pizza into a public good. Or Nouns – sparking creative ideas. And the Artist Program – funding cc0 art.

Our goal is to achieve a new and creative way to fund public goods. We're giving out grants for creative public goods projects, whether they’re big or small, with our community’s backing. We’re also making it super simple for people outside of web3 to dive in onchain.

### 🛤️ Tracks We're On

#### Gaming Track
We developed an IRL Token-based gaming experience by creating an ERC-271 Member token using thirdweb's NFT Collection contract. These tokens were symbolized as game characters, a functionality made possible through account abstraction, which is commonly used in gaming to handle inventory management; which was implemented using an ERC 6551 contract.
  
#### Coinbase Smart Wallet
We created smart wallet functionality using Thirdweb's v5 SDK. Our main mint and inventory page leverage smart wallet connection options, easing process of wallet creation.

### 🤔 Reasons to Become a Member?

- You believe in supporting Public Goods.
- You’re a meme lord, a content creator, or just someone who loves sharing cool stuff.
- Web3 beginner friendly

---

## 👘 Inside Public Goods Club

### 🛠 Tech Stack

#### Membership Token and Mint App
- thirdweb v5
- nextjs
- react
- ethers
- tailwindcss
- typescipt
- prisma
- render
- postgresql

#### Website
- Firebase
- JavaScript
- HTML/CSS
- PHP

#### PFPs (and Brand Assets)
- Photoshop
- Photo P
- Illustrator
- Udio

#### Collectibles Gallery
- Zora

### 🎨 Aesthetics

#### Design & Branding
Public Goods Club branding is a modern take on the [Pharrell:Milo Game](https://web.archive.org/web/20080723202703/http://www.pharrellwilliams.com/game/). Color wise, we have chosen a blue environment in alignment with Base's color theme. We even made our [own version of the Onchain Summer Billboard](https://zora.co/collect/base:0xa6735cb18ea3e233c535dacd7276d64db02fd9e3/1) as a mintable collectible. And as far as typography goes, [Lineal](https://velvetyne.fr/fonts/lineal/) was used for its capacity as an expressive sans-serif, conveying a feeling of freshness.

#### Character Design
Our PFP character design features over 65M generative outputs, thanks to a range of custom-feeling anatomical elements.

---

## 🚧 Development

### Areas Of Development (w/ repo links)

- [Membership Token, Smart Contract](https://github.com/W3bbieLabs/thirdweb-6551-smart-wallet)
- [Avatar Generator](https://github.com/barigyasi/avatar)
- [Brand Assets, Avatar design](https://github.com/W3bbieLabs/ONCHAIN_SUMMER_PGCDGD)
- [Website](https://github.com/W3bbieLabs/ONCHAIN_SUMMER_PGCDGD/tree/main/public_html)

### 🏁 Milestones

| Milestone Name                                       | Date Reached |
| ---------------------------------------------------- | ------------ |
| Artwork concept finalized, canvas to pfps tested out | June 10      |
| Coinbase smart wallet testing                        | June 10      |
| ERC-6551 tested                                      | June 10      |
| Commissioned artwork from collaborator               | June 17      |
| Smart features tested                                | June 17      |
| UI and website design                                | June 17      |
| ERC-6551 built                                       | June 24      |
| Website launch                                       | June 24      |
| Received artwork from collaborator                   | June 24      |
| Finalize art                                         | June 29      |
| Create mint page                                     | June 29      |
| Deploy to mainnet                                    | June 29      |
| Submit project                                       | June 30      |

### 🐞 Known Bugs

| Bug Name                  | Description                                                           | Severity (1-5) | Resolved |
| ------------------------- | --------------------------------------------------------------------- | -------------- | -------- |
| 6551 create account       | No compute on on account creation                                     | 4              | Yes      |
| 6551 view wallet bug      | Claimed token does not show after claim. Requires browser refresh.    | 2              | Yes      |
| Metamask on Safari mobile | Wallet connect fails. Other browsers and Metamask Browser functional. | 3              | No       |

_Note: Submit future bugs via Issues. This is only a temporary bug tracker._

---

## 👽 Future Plans for Public Goods Club

- Fund treasury to 10eth.
- Host onbarding event in Brussels.
- Begin accepting proposals for initial prop round. 

---

## 🦾 Team W3BBIE

| Name                                                                         | Role(s)                                                          |
| ---------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| [Kyn Adams](https://twitter.com/Tek_Gawd)                                    | Testin, Quality Assurance                                        |
| [Tabari Humphries](https://www.instagram.com/gyasi.eth/)                     | Mint and Inventory Application Development                                     |
| [Jack Lester](https://www.jack-jackjack.com)                                 | Product Design, Web/UI Development, Brand assets, Documentation  |
| [Travis Rice](https://www.linkedin.com/in/travislrice/)                      | Product Design, Project Management, Character and Asset design   |
| [Sailesh Sivakumar](https://www.linkedin.com/in/sailesh-sivakumar-453061141) | Front-end, Smart Wallet Development                              |
| [Chris Smith](https://twitter.com/_dev_og)                                   | 6551 Contract Management, 1155 Claim/Viewer                      |

---
