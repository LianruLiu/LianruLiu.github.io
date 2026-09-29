---
layout: post
title: "Hyperliquid: The Exchange That Eats Its Own Revenue"
date: 2026-09-29
categories: Finance
tags: [Hyperliquid, DeFi, Tokenomics]
---

On September 21, 2026, HYPE hit $95.17 — its third all-time high in a single week — pushing Hyperliquid's market capitalization past $22 billion and into the crypto top ten, ahead of Dogecoin. Monthly active addresses hit a record 291,900. Native lending, launched only days earlier, pulled in $269 million of borrows in its first 24 hours.

The price is the least interesting part. What matters is the machine underneath: a perpetuals exchange that routes roughly 97% of its revenue into buying its own token. No public company on earth returns capital to shareholders that aggressively. Hyperliquid does it automatically, every block, by code.

That mechanism — and the strange history that produced it — is the thing worth understanding.

---

## The Unlikely Origin — No VCs, No Marketing Department

Hyperliquid was founded by Jeff Yan, a Harvard graduate who previously worked at Hudson River Trading and ran his own market-making firm. Most DEX founders are protocol designers who have never managed a trading book. Yan had.

In 2023, he launched Hyperliquid on a custom-built Layer 1: sub-second finality, a fully on-chain central limit order book, zero gas on order placement, and a trading experience close to Binance. There was no press release, no influencer campaign, no marketing department. His philosophy, in his own words, was almost offensively simple: "create a product that users genuinely like and are willing to use." Within 100 days, daily volume crossed $1 billion.

Then came the distribution event that defined the project. On November 29, 2024, the HYPE token launched with roughly 31% of total supply — about 310 million tokens — airdropped to some 94,000 early users, fully unlocked from day one. Zero went to venture investors, because there were none. Yan had reportedly turned down funding offers that valued the project in the billions, on the grounds that VCs holding large stakes become "scars of the network." Zero went to paid market makers; he had refused those deals. Zero was reserved for centralized exchanges.

The standard interpretation is that this was generous. The better interpretation is that it was customer acquisition. A centralized exchange spends VC money on signup bonuses and KOL deals — expenses that leave the building. Hyperliquid spent equity instead, and its customers became owners: sticky, vocal, economically aligned. The marketing department was free.

## 97% of Revenue Buys Back the Token — The Assistance Fund as Dividend Policy

Strip away the narrative and Hyperliquid is, unusually for crypto, a real business. Taker fees of 0.035% and maker fees of 0.01%, on hundreds of billions in monthly volume, annualize to roughly $1.1 billion in protocol revenue — at times exceeding the fee income of Ethereum and Solana themselves. This is not token emissions dressed up as yield. It is customers paying for a service.

About 97% of those fees flow into the Assistance Fund, which buys HYPE on the open market automatically. The fund has accumulated over 44 million HYPE, worth more than $3 billion. In corporate-finance terms, that is a 97% payout ratio delivered as a continuous buyback — and it is the main reason HYPE behaves less like a governance token and more like equity. Revenue growth becomes mechanical buying pressure. The token is a claim on the exchange's cash flows with almost nothing lost to overhead in between.

The community is even debating going further: a proposal to burn a large portion of the Assistance Fund's holdings — around 13% of circulating supply — rather than merely holding the repurchased tokens. The case against is optionality; the case for is permanence. Either way, the direction of travel is clear. The protocol keeps finding ways to tighten the link between revenue and token.

## Taxing an Ecosystem, Not Just a Venue

The second half of the commercialization story is expansion: turning one venue into a platform, then taxing everything built on top of it.

HIP-3 lets outside builders deploy their own perp markets — tokenized stocks, commodities, exotics — and share the fees. Builder codes let any application plug into Hyperliquid's liquidity and monetize from day one. The community's analogy is AWS: liquidity as infrastructure, with Hyperliquid taking a cut of every workload. HyperEVM, the general smart-contract layer launched in February 2025, is the app store. Native lending, added in September 2026, adds net interest margin to the mix. Prediction markets arrived via HIP-4 in May 2026.

Then there is distribution into traditional rails: HYPE ETFs absorbing supply, NEAR building confidential perps on Hyperliquid as its execution engine, Kraken's parent moving to offer HYPE perps to US traders through the CFTC-regulated venue Bitnomial. Whether you call that adoption or new exit liquidity depends on your priors. As a business strategy, it is textbook — win the crypto-native traders first, then sell the story to Wall Street.

## The JELLY Problem

No honest account skips March 2025. An attacker deposited $7.17 million across three accounts, opened leveraged JELLY positions, and pumped the spot price more than 400% to force the HLP market-making vault into absorbing a toxic short. Hyperliquid's response: convene the validator set, vote, and delist JELLY perps — settling every position at $0.0095, the pre-manipulation price. The attacker finished roughly $1 million poorer. HYPE fell about 20% on the news.

The crisis management worked. The philosophy did not survive contact with it. A "decentralized" exchange overrode its own order book by committee vote. The validator set is small — 16 to 24 nodes, heavily foundation-weighted — and the Arbitrum bridge custodying USDC deposits is a single point of failure. Bitget's CEO called the handling "immature, unethical, and unprofessional" and reached for the "next FTX" comparison. Overblown — but the discomfort is legitimate. In a crisis, Hyperliquid's decentralization slides decisively toward the discretionary end of the spectrum.

---

## My View

My base case: the business model is genuinely innovative and genuinely fragile in the same place — its reflexivity. Volume → fees → buybacks → price → more volume is a beautiful machine in a bull market. It has never met a bear. Run it in reverse — volume dries up, the buyback bid vanishes, the price falls, traders leave — and the flywheel becomes a spiral. At a $22.6 billion market cap, with only about 26% of supply circulating (the fully diluted number is three to four times higher), the market has priced in permanent bull-market conditions.

The historical rhyme is BitMEX. Dominant perp venues rarely die by product failure. They die by regulation and competition. Hyperliquid already geofences the US, and each step into equities and prediction markets walks it further into the SEC and CFTC's line of sight. Meanwhile Lighter charges zero fees and Aster has taken roughly a fifth of the market. Liquidity is a moat until it isn't — dYdX had one once too.

None of which changes what Hyperliquid proved: you can build a multi-billion-dollar exchange without selling a share to insiders, and you can make a crypto token behave like equity by pointing nearly all real revenue at buybacks. The airdrop-as-acquisition, the ecosystem tax, the automatic bid — each is a real commercial innovation, not tokenomics theater.

---

## Conclusion

We have never seen this movie before: an exchange whose entire capital-return policy is "buy our own token," running on a chain it built itself, with no insiders on the cap table. That is exactly why it is worth watching. The first real bear market will be the audit.

## References

1. CoinDesk — "Most Influential: Jeff Yan" (Dec 2025): founder background, self-funding via Chameleon Trading, 31% airdrop, no VC allocations. https://www.coindesk.com/business/2025/12/19/most-influential-jeff-yan
2. Phemex Academy — "Who Is Jeff Yan? The Hyperliquid Founder Behind HYPE" (2026): Nov 29, 2024 TGE details, refusal of paid market makers, ~$2.9T 2025 volume. https://phemex.com/academy/jeff-yan-hyperliquid-founder-exchange
3. Gate News — "Unveiling Hyperliquid Founder Jeff Yan": token distribution breakdown (31% / 38.888% / 23.8% / 6%), "scars of the network" quote, growth timeline. https://www.gate.com/news/detail/12283139
4. insights4vc (Substack) — "Hyperliquid: Inside the $4 Trillion Onchain Market Machine": airdrop as decentralization/go-to-market/legitimacy event, HYPE as multi-function collateral. https://insights4vc.substack.com/p/hyperliquid-inside-the-4-trillion
5. Hyperliquid Community Wiki — "What is Hyperliquid": vision ("houses all of finance"), fee routing (Assistance Fund, HLP, deployers), builder codes. https://github.com/hyperliquid-community/wiki-community/blob/HEAD/introduction/what-is-hyperliquid.md
6. Hyperliquid Community Wiki — JELLY incident report (2025-03-26): timeline, validator vote to delist, settlement mechanics, post-mortem measures. https://github.com/hyperliquid-community/wiki-community/blob/HEAD/introduction/roadmap/incident/2025-26-03.md
7. onchainattack/OAK — "2025-03 Hyperliquid JELLY self-liquidation cross-venue": attacker P&L (~−$1M), HLP +$700K, HYPE −20%. https://github.com/onchainattack/oak/blob/HEAD/examples/2025-03-hyperliquid-jelly-self-liquidation-cross-venue.md
8. Bankless Times — "Hyperliquid Delists JELLY Perpetual Contracts After Suspicious Market Activity" (Mar 26, 2025). https://www.banklesstimes.com/articles/2025/03/26/hyperliquid-delists-jelly-perpetual-contracts-after-suspicious-market-activity/
9. cache256 — "Hyperliquid 2026: The Buyback Flywheel & the Control Layer": ~$1.1B annualized fees, ~$3.1B Assistance Fund, validator concentration, bridge custody risk. https://www.cache256.com/ecosystem/hyperliquid-perp-dex-infrastructure/
10. CoinLaw — "Hyperliquid Statistics 2026": $245B 30-day volume, 36.47% on-chain share, $5.9B TVL, 44.5M HYPE in Assistance Fund. https://coinlaw.io/hyperliquid-statistics/
11. Yellow Research — "Hyperliquid Owns 13% Of All Perp Volume" (Apr 2026): no-VC growth, dual-layer architecture. https://yellow.com/research/hyperliquid-perp-volume-dominance-how-2026
12. ARX — "Perp DEX Wars 2026: Hyperliquid vs Lighter vs Aster": competitive landscape, fee comparison. https://arx.trade/blog/perp-dex-wars-hyperliquid-lighter-aster/
13. tokenomics.com — "Hyperliquid Tokenomics: How HYPE Captures $65M Monthly in Holder Revenue": HIP-3 burn proposal debate. https://tokenomics.com/articles/hyperliquid-tokenomics-how-hype-captures-65m-monthly-in-holder-revenue
14. Blockonomi — "HYPE Reaches $95.17" (Sep 2026): ATH details, native lending launch, Bitnomial/Kraken proposal, 26% circulating supply. https://blockonomi.com/hyperliquid-hype-reaches-95-17-why-the-token-keeps-breaking-records/
15. Cryptopolitan — "Hyperliquid Crosses 7% of Exchange Perp Volume" (2026): Artemis data, Arthur Hayes $18M HYPE exit (June 2026). https://www.cryptopolitan.com/hyperliquid-perp-volume-market-share/

---
