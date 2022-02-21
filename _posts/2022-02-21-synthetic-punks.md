---
title: "(Unlimited) Synthetic Punks (On Chain) - Punks For Everyone / Every Ethereum Account / Address by Stephan Cilliers Et Al - What's Your Take?"
---

Stephan Cilliers¹ writes:

> I've been working on a synthetic loot spinoff for my latest project - synthetic punks.
>
> 1) Synthetic Punks stores a spritesheet [image with punk attributes] on chain and procedurally generates your [punk] avatar on the fly based on your [ethereum] address [for free].
>
> 2) You can optionally claim yours as an ERC-721 [non-fungible] token for 0.02 ETH (~ US$ 50) to support our future projects!
>
>  Check out your Synthetic Punk avatar
> at [**syntheticpunks.com**](https://syntheticpunks.com)


<!-- more -->


Comments from the [**Synthetic Punks r/ethdev**](https://old.reddit.com/r/ethdev/comments/svwgbj/onchain_unique_cryptopunks_generated_based_on/) discussion to find a valuation formula for unlimited punks:

> Is there a limit in the number of synthetic punks generated? If so, what is it?
>
> Sounds like it's unlimited. One unique punk for every [ethereum] address.
>
> Then by definition, these tokens will not make much money for the buyers. Only for the sellers. Not enough scarcity.
>
> By definition an [non-fungible] token is a speculative asset
>  and buying them in hopes they're worth more later is certainly a losing strategy.

From the Syntethic Punk F.A.Q:

> Q: Why can I claim [unlimited] random Punks?
>
> A: When you click the random button,
> it generates a brand new ethereum wallet on the fly.
> Because you can prove you own the wallet associated with the punk,
> you can claim it and have it sent to your actual ethereum wallet.


More questions and answers from the [**Synthetic Punks r/ethereum**](https://old.reddit.com/r/ethereum/comments/swdwed/onchain_unique_cryptopunks_generated_based_on/) discussion:

> Q: If I don’t claim mine, can they take it away?
>
> A: Nope, you can only claim a punk by sending
> the transaction from its associated [ethereum] address
> or signing a message proving you own the account (as is the case with claiming randomly generated punks).
>
>
> Q: You got an opensea link? That's my only hang up, I'm ready to get one otherwise.
>
> A:
> Still in the process of adding the OpenSea Collection details but it's there!
>  [See] [**opensea.io/collection/synthetic-cryptopunks**](https://opensea.io/collection/synthetic-cryptopunks).

What's your take?

Anyone has any insight what punk attributes are included in the spritesheet  (see the [**SyntheticPunksAssets**](https://etherscan.io/address/0x852aC0A51C27670751499360935a739E11533Fe0#code) contract with the base64 image encoding²)?

Some first art critique:

> The only piece of constructive [art critique] feedback I have is that the dark background is a bit too close to the black used on the outline of the punks.
>
>  Stephan Cilliers responds:
>  Thank you! In hindsight the dark background wasn't the best choice, admittedly.


Tip:  You can preview any Synthetic Punk using
[**syntheticpunks.com/#/address/0x08181F7C7FC7B06a5F88F4A400f00dC4B3F1cEA8**](https://syntheticpunks.com/#/address/0x08181F7C7FC7B06a5F88F4A400f00dC4B3F1cEA8) - that is, replace the address with another and reload the web page.



PS: Great to see the source published on github @ [**stephancill/synthetic-punks**](https://github.com/stephancill/synthetic-punks).  I try to add the [**SyntheticPunks contract**](https://etherscan.io/address/0xaf9CE4B327A3b690ABEA6F78eCCBfeFFfbEa9FDf#code) to the [**punks.contracts**](https://github.com/cryptopunksnotdead/punks.contracts) collection in the next days for further study.

---
More comments from the [**Synthetic Punks r/ethdev**](https://old.reddit.com/r/ethdev/comments/svwgbj/onchain_unique_cryptopunks_generated_based_on/) discussion. rrr_guy comments:

> We built something really similar, but instead you mine the punks with a GPU,
> and the resulting hash (instead of address) generates
> an on-chain punk,
> with collision detection agains the original project and original probabilities of traits.
>
> Probably could have saved you some [ethereum transaction] gas [fees] by using our spritesheet
> we already deployed for public usage [on September, 23rd 2021] ha!
>
> See the [**MineablePunks contract**](https://etherscan.io/address/0x595a8974c1473717c4b5d456350cd594d9bda687#code ).

---
Note ¹:  Who is Stephan Cilliers?

> Developer, studying electrical & computer engineering at University of Cape Town (UCT). Interested in technology, decentralisation of things, esports, and South Africa.
>
> Location: Cape Town, South Africa
>
>  (Source: Stephan Cilliers' Twitter Bio)

Note ²:  **Update**  I tried a quick & dirty conversion of the punk spritesheet, see [**Synthetic Punks (On Chain) Spritesheet (All 11 Archetypes and 133 Attributes) - Size : 10.77KB, 11028 Chars - Request For Comments**](2022-02-21-synthetic-punks-spritesheet.md).


