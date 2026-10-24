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

## Mailing Lists, Meetings and Bitcoin Optech
### Mailing Lists
#### [delvingbitcoin](https://delvingbitcoin.org/)
- [Bounds on chain length with BIP-54 timewarp fixes](https://delvingbitcoin.org/t/bounds-on-chain-length-with-bip-54-timewarp-fixes/2899)
- [PQC output type discussion](https://delvingbitcoin.org/t/pqc-output-type-discussion/2749/18)
- [PQLN: post-quantum security for Lightning's off-chain surfaces](https://delvingbitcoin.org/t/pqln-post-quantum-security-for-the-bitcoin-lightning-networks-off-chain-surfaces/2893/4)

### Optech
- <!--- TODO: latest [Newsletter](https://bitcoinops.org/en/newsletters/) before Nov 12 --->

## CVEs and Research
### Research
- [Zark: ZK proofs for blinded statechains](https://hackmd.io/@januszgrze/HJlHensozl) ([code](https://github.com/zerosats/zark-public))
- [Shielded Bitcoin: private transfers on L1](https://x.com/allocinitxyz/status/2103124026214568209)
    - [Glass coins vs shielded bitcoin](https://x.com/robin_linus/status/2104266654226198827)
- [Garbled Groth16 verification under 2 MB](https://eprint.iacr.org/2026/2100)
- [PRAWNS: threshold hash-based signatures](https://x.com/lclhostresearch/status/2104619822059585951)

### InfoSec
- [Liquid Network security incident assessment](https://blog.blockstream.com/liquid-network-security-incident-assessment/)
- Blink's September 19 attack: [post-mortem and bounty](https://www.blink.sv/blog/sept-19-attack-postmortem-and-bounty), [following the coins in public](https://www.blink.sv/blog/phase-two-following-the-coins-in-public)
- [Second's Ark server exploited](https://x.com/secondhq/status/2108065406665805992)
- [Core Lightning urgent security update](https://x.com/Core_LN/status/2105835841847242976)
- A rough week for general security: [roundup](https://x.com/fiveoutofnine/status/2113045722744717360), [more](https://x.com/t1o6n3y/status/2113059322339217564)
    - eMudhra CA issued keys from near-zero randomness: the same class of bug as weak wallet RNGs (Milk Sad)
    - LiteLLM 1.107.0 hijacked on PyPI: installing was enough. How exposed are Bitcoin wallets and nodes to their dependency trees?
    - 300+ malicious Tor exit relays stealing SSH passwords: what does that mean for nodes and Lightning over Tor?
    - Railway environment variables leaked: where do your hot-wallet and API keys live?
- [Anthropic's open-source vulnerability scanner](https://www.anthropic.com/research/launching-opt-in-vuln-finding-service-for-open-source)

## Pull Requests and repo updates
### [Bitcoin Core](https://github.com/bitcoin/bitcoin)
- [#36466 Make Taproot annexes standard](https://github.com/bitcoin/bitcoin/pull/36466)
- [#36277 Always complete all initial private broadcast connections](https://github.com/bitcoin/bitcoin/pull/36277)

### [lnd](https://github.com/lightningnetwork/lnd)
- [#11146 BOLT12 string codec and fuzz harnesses](https://github.com/lightningnetwork/lnd/pull/11146)

## New Releases
- Bitcoin Core 32.0 <!--- TODO: link final release if out by Nov 12, else rc --->
  ([draft release notes](https://github.com/bitcoin-core/bitcoin-devwiki/wiki/32.0-Release-Notes-Draft))
- Core Lightning [v26.06.8](https://github.com/ElementsProject/lightning/releases/tag/v26.06.8)
  and [v26.06.9](https://github.com/ElementsProject/lightning/releases/tag/v26.06.9)
- [LDK v0.2.7](https://github.com/lightningdevkit/rust-lightning/releases/tag/v0.2.7): theft and DoS fixes
- [BTCPay Server 2.4.5](https://blog.btcpayserver.org/btcpay-server-2-4-5/): security hardening

## Lightning and Payments
- [Lightning merged into the x402 spec](https://x.com/spiral_xyz/status/2102814894336672132) ([PR](https://github.com/x402-foundation/x402/pull/2861))
    - [Block joins the x402 Foundation](https://block.xyz/inside/block-joins-the-x402-foundation-to-advance-open-agentic-commerce)
- [Adding BOLT12 to @OP_RETURN_Bot with LDK](https://x.com/benthecarman/status/2108651326641213554)
- [MIT DCI vending machine back on Lightning](https://x.com/bitgould/status/2105863371463823425)

## Ecosystem
- [OpenSats grants for Bitcoin development](https://opensats.org/blog/supporting-the-foundations-of-bitcoin-development)
- [Peter Todd to lead MARA's Slipstream](https://x.com/MARAFoundation_/status/2105659425054748922)
- [FinCEN withdraws unhosted-wallet and mixing proposals](https://www.fincen.gov/news/news-releases/fincen-announces-withdrawals-proposed-digital-asset-related-rules)

## Miscellaneous
- [Bitcoin poker on MutinyNet](https://poker.bitvm.org) ([announcement](https://x.com/robin_linus/status/2108255571149480071))
- [A .bitcoin top-level domain](https://x.com/wiz/status/2108002376372347249)
