---
layout: post
type: socratic
title: "Panama Socratic 001"
permalink: /panama-socratic-001
luma: https://luma.com/497qxzxv
---

## Announcements
Please join us for the first BitDevs Panamá Socratic Seminar on **Thursday,
November 12, 5:00–7:30 PM** at the **Towerbank Blockchain Center**, CTA Dorado
Plaza. Thank you to Towerbank for the event space and the pizza.

**Please [RSVP on Luma](https://luma.com/497qxzxv)** so we can plan food and
seating. Space is limited.

We start at 5:00 and the room closes at **7:30 sharp** (building security), so
please arrive on time. Afterwards we head to TODO for beers and the rest of the
discussion. Come for that even if you can't make the main event.

Send your topic proposals to: <hello@bitdevspanama.org>,
or open a pull request against this page in
[the site repo](https://github.com/BitDevsPanama/bitdevspanama.github.io).

Reminder: the discussion is never recorded and there are no photos. We run
under the Chatham House Rule: use what you hear, don't attribute it.

Today's MC: [Matt Black](https://x.com/matthewjablack)

## Presentation

## Network Data
- [Mempool](https://mempool.space/graphs/mempool#1m), [hashrate and difficulty](https://mempool.space/graphs/mining/hashrate-difficulty#1y), [block fee rates](https://mempool.space/graphs/mining/block-fee-rates#1m)
- [TxStreet](https://txstreet.com/v/btc): watch transactions board the next block live
- [Compact block reconstruction degradation, Sept to Oct 2026](https://bnoc.xyz/t/compact-block-reconstruction-degradation-between-september-october-2026/198)

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [bitcoin-dev](https://groups.google.com/g/bitcoindev)
- [Getting BIP54 finished](https://groups.google.com/g/bitcoindev/c/TBBakeBK8_E)
    - [BIP54, the timewarp fix and forward blocks](https://groups.google.com/g/bitcoindev/c/T9s8nflvlK0)
    - [Bounds on chain length with BIP-54 timewarp fixes](https://delvingbitcoin.org/t/bounds-on-chain-length-with-bip-54-timewarp-fixes/2899)
- [Testnet 5 launch](https://groups.google.com/g/bitcoindev/c/DmFiHeo-xRw) ([kickoff](https://x.com/ajtowns/status/2112725787745092027), [BIP PR](https://github.com/bitcoin/bips/pull/2346))

#### [delvingbitcoin](https://delvingbitcoin.org/)
- [Multiplication in Tapscript today: 371 bytes, no soft fork](https://delvingbitcoin.org/t/multiplication-in-tapscript-today-371-bytes-no-soft-fork/3010)
- [BIP-110 post-mortem](https://blog.lopp.net/bip-110-post-mortem/): signaling peaked around 2.5% ([Luke Dashjr leaves OCEAN](https://www.coindesk.com/business/2026/08/31/luke-dashjr-exits-mining-pool-ocean-after-split-over-bitcoin-mining-s-future))
- Covenants: [BIP448 (TEMPLATEHASH)](https://github.com/bitcoin/bips/blob/master/bip-0448.md) demos
    - [Mercury Layer statechain wallet on Mutinynet](https://bip448.cash/)
    - [Eltoo state chain on signet: TEMPLATEHASH + CSFS + INTERNALKEY](https://delvingbitcoin.org/t/eltoo-state-chain-on-signet-third-time-templatehash-csfs-internalkey/3012)
    - [Ark (bark) on TEMPLATEHASH](https://gitlab.com/ark-bitcoin/bark/-/tree/templatehash?ref_type=heads) and [BitVM bridges with native covenants](https://robinlinus.com/bitvm448.pdf)
- Silent payments
    - [Silent Payments for multiparty wallets (AggDLEQ)](https://delvingbitcoin.org/t/silent-payments-for-multiparty-wallets/2960)
    - Bitcoin Core [#35301 BIP352 silent payments, take 2](https://github.com/bitcoin/bitcoin/pull/35301)
    - libsecp [#1929 tweak addition with actual scalars for silent payments](https://github.com/bitcoin-core/secp256k1/pull/1929)
    - [Silent payments light clients: measurements and index commitments](https://groups.google.com/g/bitcoindev/c/qqDYHnnoM7k)

### Optech
- [Newsletter #430](https://bitcoinops.org/en/newsletters/2026/11/06/) (Nov 6)
    - [TCP hole punching for nodes behind home routers](https://delvingbitcoin.org/t/tcp-hole-punching-for-bitcoin-nodes-behind-home-nats/2497/18)
    - [BIP draft: co-signer spending policies for emulating covenants](https://delvingbitcoin.org/t/bip-draft-co-signer-spending-policies/2955)
    - Quantum migration without burning coins: [QSAVE](https://groups.google.com/g/bitcoindev/c/5G38b3JL9fA) and [proof-of-decay](https://delvingbitcoin.org/t/a-novel-post-quantum-approach-proof-of-decay-cryptographic-half-life-for-unmigrated-dormant-utxos/2970)
    - [Opt-in replay protection prototype](https://delvingbitcoin.org/t/universal-opt-in-replay-protection/2792/11)
    - [BIP300: can 26% of miners censor a withdrawal?](https://groups.google.com/g/bitcoindev/c/7P0_BHRAYQI)
    - BIPs [#2205](https://github.com/bitcoin/bips/pull/2205): draft BIPs 458 to 460 for cross-input signature aggregation
- [Newsletter #429](https://bitcoinops.org/en/newsletters/2026/10/30/) (Oct 30): multiparty silent payments, a Core Lightning DoS disclosure, Core's new security policy

## Post-quantum
- [PQC output types: P2MR, P2TRv2, P2TRH](https://delvingbitcoin.org/t/pqc-output-type-discussion/2749/18)
- [SHRINCS: hash-based signatures for Bitcoin](https://github.com/SHRINCS/shrincs-bip/blob/main/SHRINCS.md) ([mailing list](https://groups.google.com/g/bitcoindev/c/HbVboXIFiG8))
- [StarkWare: first quantum-safe Bitcoin transaction mined](https://starkware.co/blog/the-first-quantum-safe-bitcoin-transaction-has-been-mined/)
- [Lopp: Bitcoin's quantum migration debate](https://blog.lopp.net/bitcoin-quantum-migration-debate): freeze exposed coins or leave them spendable?
- [Is AI going to break elliptic curve cryptography before quantum does?](https://x.com/drakefjustin/status/2107837081313505768) ([Lindell's response](https://x.com/LindellYehuda/status/2107999859219587309))
- [Project Eleven: quantum vulnerability of Bitcoin address types](https://www.projecteleven.com/blog/quantum-vulnerability-of-bitcoin-addresses) ([risk list](https://bitcoin-risq-list.projecteleven.com/))
- [PQLN: post-quantum security for Lightning's off-chain surfaces](https://delvingbitcoin.org/t/pqln-post-quantum-security-for-the-bitcoin-lightning-networks-off-chain-surfaces/2893/4)
- [localhost research: notes from a post-quantum workshop](https://lclhost.org/blog/quantum-workshop-2026/)

## CVEs and Research
### InfoSec
- [Bitcoin Core security policy update](https://groups.google.com/g/bitcoindev/c/70VSp_ARD5Q): faster fixes for easy-to-find bugs
    - [CVE-2026-117349: memory growth on paused pre-BIP31 peers](https://bitcoincore.org/en/2026/10/28/disclose-fpausesend-oom/)
    - [CVE-2026-117350: unbounded memory growth via TCP urgent data on non-Linux](https://bitcoincore.org/en/2026/10/28/disclose-tcp-oom/)
    - [CVE-2026-117346: undo file overflow](https://bitcoincore.org/en/2026/10/28/disclose-undo-overflow/)
- [Binance $6.36B hack attributed to North Korea](https://www.trmlabs.com/resources/blog/north-korea-steals-usd-6-36-billion-from-binance-in-the-largest-hack-in-history) ([Wikipedia](https://en.wikipedia.org/wiki/2026_Binance_hack))
- [Mercado Bitcoin halts withdrawals after $40M drained](https://www.coindesk.com/business/2026/11/02/brazil-s-mercado-bitcoin-halts-withdrawals-after-usd40-million-drained-across-10-chains)
- [Liquid Network exploit: 4,000 unbacked L-BTC](https://blog.blockstream.com/liquid-network-security-incident-assessment/) ([rangeproof explainer](https://drop.amboss.tech/liquid-rangeproof-explainer.html))
- [BTCPay Server hot wallets drained on 2.4.1 and earlier](https://blog.btcpayserver.org/btcpay-server-security-incident-2-4-1-and-earlier/): sweep funds, move to a fresh server
- [Coldcard Mk2/Mk3 entropy flaw drains wallets](https://www.halborn.com/blog/post/explained-the-coldcard-hack-july-2026) ([Block's write-up](https://engineering.block.xyz/blog/predictable-rng-fallback-and-32-bit-reseed-in-coldcard-firmware))
- [Air-gapped Bitcoin Core as your hardware wallet](https://pesvi.xyz/catal%C3%A0/posts/bitcoincore_airgapped_device/): one audited codebase versus more room for human error
- [Ledger hardware implant attack](https://www.ledger.com/blog-response-hardware-implant-attack) ([estimated losses](https://x.com/SpecterAnalyst/status/2108534068564373687))
- [Your HDMI cable leaks your screen: Deep-TEMPEST](https://arxiv.org/abs/2407.09717) ([demo](https://x.com/Psalteric/status/2119554566165577768), [TempestSDR](https://github.com/aalex954/tempest-sdr-demo))
- [DoS vulnerabilities fixed in Eclair v0.14.0](https://delvingbitcoin.org/t/disclosure-dos-vulnerabilities-fixed-in-eclair-v0-14-0/2914)
- Blink's September 19 attack: [post-mortem and bounty](https://www.blink.sv/blog/sept-19-attack-postmortem-and-bounty), [following the coins in public](https://www.blink.sv/blog/phase-two-following-the-coins-in-public)
- [Second's Ark server exploited](https://x.com/secondhq/status/2108065406665805992)
- [App Store "non-custodial" wallets decompiled](https://kek.lol/research/appstore-wallets/): 45 of 494 flagged for sending seeds to servers or using `Math.random`

### Physical security
- [Mexico: killings in Atizapán linked to bitcoin](https://politica.expansion.mx/estados/2026/09/05/caso-jonathan-melendez-bitcoins-movil-asesinato-atizapan)

### Research
- [Garbled Groth16 verification under 2 MB](https://eprint.iacr.org/2026/2100) and [Argo](https://eprint.iacr.org/2026/2165): what this means for BitVM
- [Compact Shielded CSV](https://arxiv.org/abs/2609.32015)
- [Claude traces the origins of the NIST P-256 curve seeds](https://www.anthropic.com/research/ecdsa-curve-origins)
- [Zark: ZK proofs for blinded statechains](https://hackmd.io/@januszgrze/HJlHensozl) ([code](https://github.com/zerosats/zark-public))
- [Shielded Bitcoin: private transfers on L1](https://x.com/allocinitxyz/status/2103124026214568209)
    - [Glass coins vs shielded bitcoin](https://x.com/robin_linus/status/2104266654226198827)
- [Lichen: L2s in channels enforced on bitcoin](https://github.com/AdamISZ/lichen/blob/master/papers/lichen-v0.4.1.pdf)
- [PRAWNS: threshold hash-based signatures](https://x.com/lclhostresearch/status/2104619822059585951)
- [Snail: zero on-chain fee bitcoin transactions](https://gitlab.com/1440000bytes/snail)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [#36466 Make Taproot annexes standard](https://github.com/bitcoin/bitcoin/pull/36466)
- [#36277 Always complete all initial private broadcast connections](https://github.com/bitcoin/bitcoin/pull/36277)

### [lnd](https://github.com/lightningnetwork/lnd)
- [#11146 BOLT12 string codec and fuzz harnesses](https://github.com/lightningnetwork/lnd/pull/11146)

## New Releases
- [Bitcoin Core v32.1](https://bitcoincore.org/en/releases/32.1/) ([release notes](https://github.com/bitcoin/bitcoin/blob/master/doc/release-notes/release-notes-32.1.md))
- [rbitcoin v0.7.0](https://github.com/reardencode/rbitcoin/releases/tag/v0.7.0): an independent Rust node, [written by AI under Rearden's direction](https://rbitcoin.org/about/index.html)
    - [Would you trust an AI-written bitcoin node?](https://stacker.news/items/1598294)
- Core Lightning [v26.06.8](https://github.com/ElementsProject/lightning/releases/tag/v26.06.8)
  and [v26.06.9](https://github.com/ElementsProject/lightning/releases/tag/v26.06.9)
- [LDK v0.2.7](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.2.7): theft and DoS fixes
- [LDK v0.3-rc3](https://git.rust-bitcoin.org/lightningdevkit/rust-lightning/releases/tag/v0.3-rc3)
- [BTCPay Server 2.4.7](https://github.com/btcpayserver/btcpayserver/releases/tag/v2.4.7)

## Lightning and Payments
- lnd vulnerabilities
    - [Linux kernel MPTCP exploit hits lnd and other Go services](https://x.com/thebluematt/status/2116129367986450764) ([Peter Todd](https://x.com/peterktodd/status/2116039505954185279)); [LND v0.21.6](https://github.com/lightningnetwork/lnd/releases/tag/v0.21.6-beta) disables MPTCP listeners, but patch the kernel too
    - [lnd doesn't wait for enough confirmations when closing channels](https://delvingbitcoin.org/t/disclosure-lnd-doesnt-wait-for-enough-confirmations-when-closing-channels/2800)
- [fiatjaf declares Lightning broken beyond repair](https://lightning.news/fiatjaf-drivechain-declaring-lightning-broken-beyond-repair/) ([video](https://www.youtube.com/watch?v=2PD9UsU_jY4))
- [Lightning merged into the x402 spec](https://github.com/x402-foundation/x402/pull/2861): x402 revives HTTP 402 "Payment Required" so apps and AI agents can pay per request
    - [Spiral's announcement](https://x.com/spiral_xyz/status/2102814894336672132)
    - [Block joins the x402 Foundation](https://block.xyz/inside/block-joins-the-x402-foundation-to-advance-open-agentic-commerce)

## Policy and regulation
- Panamá: where is the crypto law?
    - [Ley cripto: el segundo intento de la Asamblea](https://www.laestrella.com.pa/economia/ley-cripto-el-segundo-intento-de-la-asamblea-y-la-postura-del-sector-HB12134416): Proyecto de Ley 247 would create a Consejo Nacional de Activos Digitales and register VASPs with the UAF. Still in subcommittee
    - The 2022 "Ley Bitcoin" (Proyecto 697) was declared unenforceable by the Supreme Court in July 2023
    - [Criptoactivos en Panamá: reglas para exchanges y tokenización](https://lexlatin.com/entrevistas/criptoactivos-panama-reglas-exchanges-tokenizacion)
- [CLARITY Act stalls in the Senate, 49 to 50](https://apnews.com/article/e3caf262dc138147941787299e5f0a66) ([Galaxy postmortem](https://www.galaxy.com/insights/research/clarity-act-failed-senate-vote-49-50-postmortem-crypto-regulation-2026), [Coin Center on BRCA changes](https://coincenter.org/the-proposed-brca-changes-are-a-tough-pill-to-swallow/))
- [FinCEN withdraws its unhosted-wallet and mixer rules](https://www.fincen.gov/news/news-releases/fincen-announces-withdrawals-proposed-digital-asset-related-rules)
- [Brazil: self-custody transfers enter COAF reporting (BCB Resolution 591)](https://www.bcb.gov.br/estabilidadefinanceira/exibenormativo?tipo=Resolu%C3%A7%C3%A3o%20BCB&numero=591)

## Ecosystem
- [Peter Todd revives tail emission](https://livecoins.com.br/emissao-de-cauda-pode-ser-a-proxima-grande-polemica-do-bitcoin-entenda-a-proposta/)
- [Alkanes: smart contracts on Bitcoin without a soft fork](https://decrypt.co/327721/bitcoin-alkanes-next-big-btc-innovation-after-ordinals-and-runes) ([61% of transactions for 90 days](https://bitcoinmagazine.com/news/alkanes-drove-61-of-bitcoin-transactions-for-90-days-subfrost-data-shows))
- [OpenSats grants for Bitcoin development](https://opensats.org/blog/supporting-the-foundations-of-bitcoin-development)

## Just for fun
- [Bitcoin poker on MutinyNet](https://poker.bitvm.org) ([announcement](https://x.com/robin_linus/status/2108255571149480071), [paper](https://robinlinus.com/bitcoin-poker.pdf))
- [Savepoint Signer: PSBT signing inside Pokémon Crystal on a Game Boy](https://github.com/alvroble/savepoint-signer)
- [A .bitcoin top-level domain](https://x.com/wiz/status/2108002376372347249)
- [NDS-Signer: SeedSigner on a Nintendo DSi](https://github.com/ndssigner/nds-signer) ([Stacker News](https://stacker.news/items/1592478))
- [Steal My Bitcoin honeypot](https://stealmybitcoin.com/) ([winning exploit chain](https://github.com/KillaBoi/StealMyBitcoin-PoC))
