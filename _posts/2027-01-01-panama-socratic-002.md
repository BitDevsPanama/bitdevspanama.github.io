---
layout: post
type: socratic
title: "Panama Socratic 002"
permalink: /panama-socratic-002
date_display: "TBD Jan 2027"
---
<!--- TODO: once the date is set, rename this file to the real date, drop date_display, add the luma: link and fill in the time below --->

## Announcements
Please join us for the second BitDevs Panamá Socratic Seminar in **January
2027** at the **Towerbank Blockchain Center**, CTA Dorado Plaza. The exact date
is still to be confirmed. Thank you to Towerbank for the event space.

We'll post the date and the Luma RSVP link here as soon as they're set. Space is
limited, so please RSVP once it's up.

The room closes on time because of building security, so please arrive on
time. Afterwards we head somewhere nearby for beers and the rest of the
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
- [Compact block reconstruction got worse from September to October](https://bnoc.xyz/t/compact-block-reconstruction-degradation-between-september-october-2026/198): chains of cheap rune mints made mempools diverge, and blocks that rebuilt with no extra round trip fell to 10% or less

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [bitcoin-dev](https://groups.google.com/g/bitcoindev)
- [Great Script Restoration: Tapleaf 0xc2](https://groups.google.com/g/bitcoindev/c/wTUXHpzpV60): bring back the disabled opcodes under a new tapleaf version
- [Draft BIPs: anti-exfil signing for BIP340 and ECDSA](https://groups.google.com/g/bitcoindev/c/cB37_jChkEI): the host mixes randomness into the nonce so a malicious signer can't leak your key through its signatures
- Encrypted wallet backups: [BIP138 encrypted descriptors](https://github.com/bitcoin/bips/blob/master/bip-0138.md) and a [wallet label sync draft](https://groups.google.com/g/bitcoindev/c/p6UUOdGi9YI), safe to keep in the cloud
- New P2P proposals: [Stale Tip Relay](https://groups.google.com/g/bitcoindev/c/AwOPNxF15mU), [Transport Feature Negotiation](https://groups.google.com/g/bitcoindev/c/LbTSN08fYlM) and [BIP324 one-byte message aliases](https://groups.google.com/g/bitcoindev/c/YjrkzS_Sjes)
- [BIP draft: NestedMuSig2](https://groups.google.com/g/bitcoindev/c/eSgxP8NmEnA): MuSig2 groups inside MuSig2 groups, still one BIP340 signature
- [Two years of BIP editing, time for new faces?](https://groups.google.com/g/bitcoindev/c/zCmHEGbCADQ): Murch proposes three active editors

#### [delvingbitcoin](https://delvingbitcoin.org/)
- [Descriptor syntax for hash preimages](https://delvingbitcoin.org/t/descriptor-syntax-for-hash-preimages/2935): `sha256(preimage(HEX))` for wallets that use hashlocks
- [Comparing covenant proposals for vaults](https://delvingbitcoin.org/t/comparing-bitcoin-covenant-proposals-for-vaults/2877): side by side, useful context after TEMPLATEHASH at 001
- [Depots: theft-proof self-custody for billions](https://delvingbitcoin.org/t/depots-theft-proof-self-custodial-bitcoin-for-billions-of-users/2892): John Law's probabilistic channels, needs CTV and CSFS
- [Should wallets default to Taproot or SegWit receive addresses?](https://delvingbitcoin.org/t/should-wallets-default-to-taproot-or-segwit-receive-addresses-while-some-services-still-reject-bc1p/3056): some services still reject bc1p
- [Open question: a "slow-sliding MTP" attack from BIP54?](https://delvingbitcoin.org/t/open-question-on-a-hypothetical-minor-slow-sliding-mtp-attack-introduced-by-bip-54/3101)
- [Checking transaction inclusion against an untrusted explorer: how much PoW is enough?](https://delvingbitcoin.org/t/checking-transaction-inclusion-against-an-untrusted-explorer-api-how-much-proof-of-work-is-enough/3113)
- Faster bootstrapping: [P2P UTXO set sharing (BIP452)](https://gnusha.org/pi/bitcoindev/atCSAVprBE-tAnN3@erisian.com.au/) and [SwiftSync building Utreexo during IBD](https://delvingbitcoin.org/t/implicit-deletions-and-improvements-in-utreexo-ibd/2881/4)

### Meetings
- [Testnet5 is live](https://groups.google.com/g/bitcoindev/c/aF5fLs9oZNk): the genesis block was [ASIC-mined in public](https://gist.github.com/ajtowns/ebb148819c6028387271e6f0dce5e1da) ([BIPs #2356](https://github.com/bitcoin/bips/pull/2356))
- [CoreDev October 2026 transcripts](https://btctranscripts.com/bitcoin-core-dev-tech/2026-10)

### Optech
- [Newsletter #432](https://bitcoinops.org/en/newsletters/2026/11/20/) (Nov 20)
    - [Decentralized Coinbase Payout Protocols (DCPP)](https://delvingbitcoin.org/t/decentralized-coinbase-payout-protocols-dcpp-a-framework-for-discussion/3060): pools paying miners straight from the coinbase, and the "rich list attack" on small miners
    - [Bull Bitcoin makes payjoin the default](https://www.bullbitcoin.com/blog/payjoin-trading) for exchange orders
    - [COLDCARD adds codex32 backups](https://blog.coinkite.com/coldcard-firmware-563-153q/)
    - [Stratum v2 apps v0.9.0](https://github.com/stratum-mining/sv2-apps/releases/tag/v0.9.0): MARA and Foundry announce adoption
- [Newsletter #431](https://bitcoinops.org/en/newsletters/2026/11/13/) (Nov 13)
    - Anti-exfil BIPs, three Core disclosures (see InfoSec), testnet5 genesis mining, compact block degradation
    - [BIPs #2251](https://github.com/bitcoin/bips/pull/2251): BIP394 `rawtr()` descriptors, with a warning that hidden script paths may exist

## Post-quantum
- What to do with coins that never migrate?
    - [Quantum landmines and vulnerable coin auctions](https://groups.google.com/g/bitcoindev/c/ARMwWdWcz9A) (Cory Fields)
    - [Post Quantum Recovery Framework](https://delvingbitcoin.org/t/post-quantum-recovery-framework/3099) (adiabat)
    - [35.6% of BTC already sits behind exposed keys or scripts](https://delvingbitcoin.org/t/how-much-btc-sits-behind-keys-or-scripts-already-on-chain-block-975-019/3088): 7.16M BTC at block 975,019
- New schemes and formats
    - [BIP draft: bc1z addresses using ML-DSA-65](https://delvingbitcoin.org/t/bip-draft-post-quantum-address-format-bc1z-using-ml-dsa-65/3067): lattice signatures, versus SHRINCS's hash-based ones ([mailing list](https://groups.google.com/g/bitcoindev/c/dS0_Hg142RE))
    - [CUTS: Chained Uniform-sum Tree Signatures](https://www.projecteleven.com/blog/introducing-cuts-a-new-few-time-hash-based-signature-scheme) ([eprint](https://eprint.iacr.org/2026/2455))
    - [Block-wide signature aggregation via SNARKs](https://delvingbitcoin.org/t/block-wide-signature-aggregation-via-snarks/2875): one answer to huge PQ signatures
    - Post-quantum transport: [ML-KEM key establishment](https://groups.google.com/g/bitcoindev/c/StlxwS4aBwE) and [a PQ path for BIP324](https://groups.google.com/g/bitcoindev/c/n_5WuKVYqwI/m/lBooLis3AQAJ)
    - [Toward efficient post-quantum bitcoin bridges](https://delvingbitcoin.org/t/toward-efficient-post-quantum-bitcoin-bridges/3079)
- How close is the threat?
    - [Shor on cat qubits: RSA-2048 with 22,593 qubits in 3.14 days](https://eprint.iacr.org/2026/2665)
    - [A subexponential-time algorithm for elliptic curve discrete log?](https://github.com/bochum-crypto/subexponential-ecdl/blob/main/subexponential-ecdl.pdf) Read skeptically
    - [Claude halves the security of HAWK, a post-quantum signature](https://www.anthropic.com/research/discovering-cryptographic-weaknesses): new schemes break too
    - [Coinbase on Bitcoin's quantum readiness](https://www.coinbase.com/blog/working-together-on-btc-post-quantum-readiness)

## CVEs and Research
### InfoSec
- Bitcoin Core disclosures
    - [CVE-2026-117348: node stall through duplicate orphan announcements](https://bitcoincore.org/en/2026/11/20/disclose-orphan-inv-stall/): fixed in 31.3 and 30.5, no fix for 29.x
    - [CVE-2025-62861: TRUC sibling eviction stops block template creation](https://bitcoincore.org/en/2026/11/10/disclose-cve-2025-62861/)
    - [CVE-2025-62860: inbound Tor peers got whitelist permissions](https://bitcoincore.org/en/2026/11/10/disclose-cve-2025-62860/) ([Antoine Poinsot's write-up](https://antoinep.com/posts/cve-2025-62860/))
    - [CVE-2025-62859: witness malleation stalls block processing](https://bitcoincore.org/en/2026/11/10/disclose-cve-2025-62859/)
- [Electrum: a malicious server fakes an RBF replacement](https://github.com/spesmilo/electrum/security/advisories/GHSA-6jp4-8v48-cc5v): exploited in the wild. Bump the fee and you sign the attacker's outputs. Update to 4.8.3
- The AI bug wave
    - [Anthropic's opt-in vulnerability-finding service for open source](https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source): the source of the findings behind BTCPay 2.4.7
    - [PHP2Shell: two unauthenticated PHP RCEs found with AI](https://www.wiz.io/blog/php2shell-php-rce): how the Steal My Bitcoin honeypot from 001 fell
    - [bitcoinjs-lib: six advisories](https://github.com/bitcoinjs/bitcoinjs-lib/security/advisories), including PSBT fee underestimation
    - [CyberCartel used AI agents against 400+ Latin American financial firms](https://www.straiker.ai/blog/inside-carliy0s-how-cybercartel-used-multiple-ai-models-to-attack-latin-american-banks)
- Hardware wallet supply chain, beyond Ledger
    - [Keystone's genuine-check key stolen, 18,835 devices to be destroyed](https://x.com/KeystoneWallet/status/2114719318722404578)
    - [Foundation phishing sent from its own domains](https://x.com/FoundationHQ/status/2114743519852069110)
    - [Ngrave fake push alerts, about $2.56M lost](https://www.ngrave.io/en/blog/incident-report-fake-liquid-security-alert-17-october)
    - [Trezor shipping partner Skladon breached](https://trezor.io/blog/news/data-breach-at-trezor-shipping-partner-skladon)
- [LNbits tells all operators to shut down](https://thehackernews.com/2026/11/lnbits-urges-all-operators-to-shut-down.html)
- [eMudhra: eight intermediate CAs with 8-bit keys](https://scotthelme.co.uk/eight-bits-of-trust-emudhras-ca-keys-cracked-in-milliseconds/): Electrum, BTCPay, Alby Hub and Bitaxe dropped trust
- [BOLT11: reject invoices with duplicate payment hashes](https://github.com/lightning/bolts/pull/1357): LNP2PBot got paid twice
- Lightning DoS and theft fixes: [Eclair trampoline theft (0.14.5)](https://github.com/ACINQ/eclair/releases/tag/v0.14.5), [Eclair 0.14.0 memory exhaustion](https://delvingbitcoin.org/t/disclosure-memory-exhaustion-dos-in-eclair-0-14-0/3057), [CLN funding outpoint reuse crash](https://delvingbitcoin.org/t/disclosure-dos-vulnerability-fixed-in-core-lightning-v26-06-8/3072)
- [333 Tor exits intercepted SSH to steal passwords](https://kaba.cx/posts/20261020_Tor/)
- [Chainalysis breach exposed credentials for all customers](https://www.bleepingcomputer.com/news/security/chainalysis-says-breach-exposed-credentials-for-all-customers/)
- [Nubank pauses crypto withdrawals](https://www.disruptionbanking.com/2026/11/06/nubank-pauses-crypto-withdrawals-and-deposits-points-to-external-verification-provider/)

### Physical security
- [Lopp's wrench-attack list doubles to 702](https://github.com/jlopp/physical-bitcoin-attacks/pull/234)

### Research
- [STARK proof of the UTXO set at block 972,500, circuits proven in Lean](https://delvingbitcoin.org/t/a-stark-proof-of-bitcoins-utxo-set-at-block-972-500-with-circuits-proven-in-lean/3070): a step toward trustless fast sync
- [LN-GAP: Lightning governed by arbitrary programs](https://github.com/AdamISZ/ln-gap/blob/master/docs/paper/lngap-short.pdf): chess inside a channel, the companion to Lichen from 001 ([mailing list](https://groups.google.com/g/bitcoindev/c/pjv6bL_42kg))
- [LayerTree (Lightning Labs)](https://layertree.tech/paper/main.pdf): a shared UTXO with one-transaction unilateral exit, needs OP_CAT and OP_TWEAKADD
- [Machine-checked soundness of BIP340 batch verification](https://delvingbitcoin.org/t/machine-checked-soundness-of-bip340-batch-verification-with-128-bit-derived-randomizers/3019): a Lean proof that unlocks about 9% faster batch verification
- [MuCPay: scriptless multi-party oracle-based conditional payments](https://eprint.iacr.org/2026/2732): breaks the quadratic cost of DLC-style payments
- [Who patches the Lightning Network?](https://arxiv.org/abs/2610.30350): nodes upgrade on Umbrel's schedule, not when advisories come out
- [Hornet: an executable specification of consensus](https://github.com/tobysharp/hornet)
- [Exposure-aware transaction construction](https://groups.google.com/g/bitcoindev/c/LcczFuBQjsE): coin selection with public-key exposure in mind

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [#36629 Output script index and script history RPC](https://github.com/bitcoin/bitcoin/pull/36629): an address index in Core, works pruned
- [#36757 Tor and I2P peers can no longer change your advertised address](https://github.com/bitcoin/bitcoin/pull/36757)
- [#36142 Validate Tor onion service replies](https://github.com/bitcoin/bitcoin/pull/36142): fixes a Tor control command injection
- [#35752 Wallet encryption could leave keys in the clear](https://github.com/bitcoin/bitcoin/pull/35752)
- [#36338 A malleated P2PKH hid silent payments](https://github.com/bitcoin/bitcoin/pull/36338)
- [dergoegge steps down as maintainer](https://github.com/bitcoin/bitcoin/pull/36335) ([his post](https://www.dergoegge.de/blog/somethings-been-bugging-me.html))

### [BIPs](https://github.com/bitcoin/bips)
- [BIP458 half-aggregation](https://github.com/bitcoin/bips/blob/master/bip-0458.mediawiki), [BIP459 DahLIAS](https://github.com/bitcoin/bips/blob/master/bip-0459.mediawiki) and [BIP460 CISA](https://github.com/bitcoin/bips/blob/master/bip-0460.mediawiki) are merged (drafts at 001). See them in action in the [Bitcoin Pisa payjoin demo](https://github.com/bitcoin-pisa)
- [BIP139 wallet metadata backup format](https://github.com/bitcoin/bips/pull/2130) merged

### [BOLTs](https://github.com/lightning/bolts) and Lightning implementations
- Simple taproot channels getting close: [BOLTs #1352](https://github.com/lightning/bolts/pull/1352) and [LDK feature bits 80/81](https://git.rust-bitcoin.org/lightningdevkit/rust-lightning/pulls/5189)
- [BOLTs #1367 onion messages v2](https://github.com/lightning/bolts/pull/1367)
- lnd: [#10919 local reputation against channel jamming](https://github.com/lightningnetwork/lnd/pull/10919), experimental BOLT12 ([#11340](https://github.com/lightningnetwork/lnd/pull/11340), [#11374](https://github.com/lightningnetwork/lnd/pull/11374))
- CLN [#9730 `lightning-hsmtool recoverhtlc`](https://github.com/ElementsProject/lightning/pull/9730): recover HTLC outputs after losing channel state

## New Releases
- [Bitcoin Core 31.3](https://bitcoincore.org/en/2026/11/20/release-31.3/) and [30.5](https://bitcoincore.org/en/2026/11/20/release-30.5/)
- [LND v0.21.8-beta](https://github.com/lightningnetwork/lnd/releases/tag/v0.21.8-beta), [LDK v0.2.8](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.2.8), [Core Lightning v26.12rc1](https://github.com/ElementsProject/lightning/releases/tag/v26.12rc1) (`xpay` replaces `pay` in 27.03), [Eclair v0.14.1](https://github.com/ACINQ/eclair/releases/tag/v0.14.1)
- [rbitcoin 0.9.0](https://github.com/rbitcoin-org/rbitcoin/releases/tag/v0.9.0): consensus now checked against Hornet (follow-up to 001)
- Payjoin v1 out, async payjoin in: [payjoin-cli 1.0.0](https://github.com/payjoin/rust-payjoin/releases/tag/payjoin-cli-1.0.0), while [Wasabi 2.8.5 drops BIP78](https://github.com/WalletWasabi/WalletWasabi/releases/tag/v2.8.5)
- [Liana v16.0](https://github.com/wizardsardine/liana/releases/tag/v16.0): taproot by default, BIP138 encrypted backups
- [Floresta Desktop](https://github.com/cristiansolutchak/floresta-desktop): a Utreexo node with a GUI
- [Mostro v0.20.0](https://github.com/MostroP2P/mostro/releases/tag/v0.20.0): the Nostr P2P exchange

## Lightning and Payments
- [Wavelength on mainnet](https://lightning.engineering/posts/2026-10-23-wavelength-mainnet-launch/): Lightning Labs' Ark-style toolkit, capped at 300k sats
- [The Long Road to Bitcoin Payments](https://delvingbitcoin.org/t/the-long-road-to-bitcoin-payments/2987) (Spiral): a million merchants can accept bitcoin and almost nobody pays with it
- [Cassis: multi-layer, multi-hop HTLC routing](https://delvingbitcoin.org/t/cassis-a-new-simple-scheme-for-generic-multi-layer-multi-hop-htlc-routing/2952): one hash across LN, Liquid, Cashu, Fedimint, Ark and on-chain
- [OpenReceive: receive-only Lightning checkout via NWC](https://github.com/OpenReceive/openreceive): a hacked server can't spend
- Explorers for the new layers: [spark.observer](https://spark.observer/) and [ark.observer](https://ark.observer/)
- [Lightning in the BitBoxApp](https://blog.bitbox.swiss/en/introducing-lightning-in-the-bitboxapp/)

## Policy and regulation
- Panamá: any movement on Proyecto de Ley 247? <!--- TODO: check status before the event --->
- [Paraguay seizes digital bank ueno](https://apnews.com/article/paraguay-ueno-digital-bank-seizure-santiago-pena-9d7521ddee45a185d2618c7e09a243a3)
- [Mexico's Ley de Economía Digital](https://gaceta.diputados.gob.mx/PDF/66/2026/oct/20261006-IV.pdf): Hacienda could mandate digital-only payments
- [France: committee approves declaring self-custody wallets holding €100k or more](https://www.assemblee-nationale.fr/dyn/17/amendements/3210A/CION_FIN/CF821)
- [SEC proposes crypto custody rules for advisers and funds](https://www.govinfo.gov/content/pkg/FR-2026-10-06/html/2026-20466.htm)

## Mining
- [Binance Pool shuts down](https://www.binance.com/en/support/announcement/detail/2b45800173fd44f48b4517f25f941434): about 1.6% of blocks
- [ArkPool: a Bitaxe pool paying hourly over Ark](https://arkpool.org/), and [silent payment coinbase payouts](https://delvingbitcoin.org/t/silent-payments-coinbase/2833)
- [eCash (BIP300 fork) live on mainnet since block 973,728](https://dashboard.ecash.com/?network=mainnet)

## Ecosystem
- [OpenSats red-team grants](https://opensats.org/blog/red-team-grants-first-set)
- [TABConf 8, the last one](https://8.tabconf.com/history/)

## Just for fun
- [EntropyLab](https://entropylab.online/) ([source](https://github.com/OogaBoogaX/entropylab)): turn dice, cards or coins into a seed offline, with a live chi-square test on your die. A follow-up to 001's diceware discussion
- [The whitepaper stored in a taproot annex](https://mempool.space/tx/52bc40e5123f7ca2351a14adaa26d05f9a85a9f4185a0667359c317fa33eadb8?showDetails=true)
- [Coldcard Q as a Game Boy emulator](https://github.com/benthecarman/coldcard-gb)
- [floppy39](https://gitlab.com/1440000bytes/floppy39): a bootable floppy that generates seeds
- [The bitcoin-dev mailing list, made readable](https://delvingbitcoin.org/t/we-made-the-bitcoin-dev-mailing-list-readable-15-years-24-699-messages/2985): 15 years, 24,699 messages
- [covenants.diy](https://covenants.diy/)
- [Softfork before GTA VI?](https://delvingbitcoin.org/t/softfork-before-gta-vi)
