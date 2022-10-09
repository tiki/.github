# TIKI: choose better data   
### ⛏ Infrastructure for the new data economy —built for those building it.

- 🤑 **Add data incentive programs**  
like discounts, loyalty programs, and gated features to your product.  
*Did you know, without an incentive, <20% of US iOS users opt-in to data [tracking](https://support.apple.com/en-us/HT212025)?*  

- 🦺 **Reduce risk and compliance costs**  
with managed consent and an immutable audit trail.  
*Did you know [71%](https://unctad.org/page/data-protection-and-privacy-legislation-worldwide) of the world’s countries have data protection and privacy legislation?*  

- 📈 **Buy/Sell/License**  
zero, first, and third-party data (legally), with automated provenance and ownership rights.   
*coming soon.*  

---

### ⛔️ All-encompassing ToS don't cut it anymore. 
[People](https://www.cisco.com/c/dam/en_us/about/doing_business/trust-center/docs/cisco-cybersecurity-series-2021-cps.pdf) expect more transparency, control, and compensation for their data.  
**The result:** privacy requirements piling up and  [abysmal](https://www.flurry.com/blog/att-opt-in-rate-monthly-updates/) opt-in rates.

The thing is, less data isn't the answer...  `less data = worse products & services` 

---
### 🤖 How it works
 
TIKI is a **decentralized data exchange** (DEX) built on ⛓ [blockchain tech](https://github.com/tiki/.github/blob/main/profile/WHITEPAPER-2CHAINZ.md), enabling direct people-to-business data trade —meeting privacy requirements while maximizing the flow of data.

The basics: 

- 🧾 **User Data Ownership** - tokenized (NFT) records of data point, pool, or stream ownership —akin to a digital version of a [property title](https://en.wikipedia.org/wiki/Title_(property)) (e.g., house or car).  

- ⚖️ **On-chain Consent** - an immutable, sequential audit trail for the contractual licensing of user-owned data —like digital versions of [deeds](https://en.wikipedia.org/wiki/Deed#Requirements).   

- 📱 **Edge Based** - using a relative/no consensus model, ownership minting and consent handling happens in real-time, at the application layer, for free (up to 1M MAUs). 

*No significant compute, network, or storage overhead. No change to existing backend systems required. Anonymous to TIKI.*

## 🧙‍♂️ Get Started

**No expertise in data, privacy, or crypto needed.**  
*(But if you have some, everything is open source. Throw us a PR.)*

Our DEX is a growing collection of SDKs, APIs, and templates to help you quickly build the features you want and get the data you need.

*Launching end of October 🚀. Stay Tuned!*

## 🧑‍💻 Work in Progress.  
We prioritize **user-centricity, transparency, and trust** above all else. 

#### SDK(s)
The primary method for using TIKI. Refer to platform-specific SDKs for supported features and docs. 

- **Flutter**: [tiki-sdk-flutter](https://github.com/tiki/tiki-sdk-flutter) - Combines Dart SDK with Flutter-specific storage libs. Just add to your pubspec.

- **Dart**: [tiki-sdk-dart](https://github.com/tiki/tiki-sdk-dart) - Core implementation including blockchain (assembler, validator, wallet, etc.), ownership minting, and consent handling. Used by Flutter, iOS, and Android SDKs.

#### Layer 0
Services to support the TIKI blockchain (Layer 1) —most commonly used in interoperability or to simplify common implementation challenges.

- **LT Block Storage**: [l0-storage](https://github.com/tiki/l0-storage) - Provides long-term (10+ years) immutable (WORM) low-frequency read block storage in a cloud-hosted bucket. 

#### Mobile App
For people to take data ownership a step further. More control, more transparency, and more compensation.

- **App:** [app](https://github.com/tiki/app)
- **Supporting Libs:** [app-data](https://github.com/tiki/app-data), [app-strategy-msft](https://github.com/tiki/app-strategy-msft), [app-strategy-goog](https://github.com/tiki/app-strategy-goog), [app-login](https://github.com/tiki/app-login), [dart-httpp](https://github.com/tiki/dart-httpp), [app-wallet](https://github.com/tiki/app-wallet), [app-syncchain](https://github.com/tiki/app-syncchain), [app-account](https://github.com/tiki/app-account), [app-decision](https://github.com/tiki/app-decision), [app-carousel](https://github.com/tiki/app-carousel), [app-style](https://github.com/tiki/app-style), [app-localchain](https://github.com/tiki/app-localchain), [app-localgraph](https://github.com/tiki/app-localgraph), [app-money](https://github.com/tiki/app-money), [flutter-kv](https://github.com/tiki/flutter-kv), [app-spam-card](https://github.com/tiki/app-spam-card), [flutter-zendesk](https://github.com/tiki/flutter-zendesk), [flutter-upvoty](https://github.com/tiki/flutter-upvoty)
- **Backend Services**: [app-bouncer](https://github.com/tiki/app-bouncer)

#### Data Pools
Contextual, anonymous data pooling using knowledge graphs with weighted edges (# of users). The objective is to combine multi-user data for licensing while protecting the privacy of originators (without synthetics or noise).

- **Knowledge Graph**: [pool-kgraph](https://github.com/tiki/pool-kgraph)
- **Ingestion Breakers** [pool-ingest](https://github.com/tiki/pool-ingest)

## 👋 Get Involved

Care about decentralizing data ownership?  
*Or, as we like to put it, "unfucking the internet."*

🌐 [mytiki.com](https://mytiki.com)  
👾 [discord.gg/tiki](https://discord.gg/tiki)  
📚 [mytiki.substack.com](https://blog.mytiki.com)  
🐦 [@my_tiki_](https://twitter.com/my_tiki_)

### 🍍Team  
*Those who have a 'why' to live, can bear with almost any 'how'* —Nietzsche via Frankl.  

- Tiki Mike ([@mike-audi](https://github.com/mike-audi)) - Founder & CEO 
- Shane Faria ([@sfaria27](https://github.com/sfaria27)) - Co-founder & Head of Content
- Blockchain Barry ([@BOC111](https://github.com/BOC111)) - Governance
- Ricardo Gonçalves ([@ricardobrg](https://github.com/ricardobrg)) - Mobile Lead

**We're hiring:** [angel.co/company/mytiki/jobs](https://angel.co/company/mytiki/jobs)

### 🤠 H/T
- Nick Gebo ([@NickkTMD](https://github.com/NickkTMD))
- Diana Shaw
- Daniel Tierney
- Bhaskar Ram ([@bhaskarvilles](https://github.com/bhaskarvilles))
- Thomas Rokicki ([@CraftingGamerTom](https://github.com/CraftingGamerTom))

### 🍹 Backed By
- [11 Tribes Ventures](https://11tribes.vc), [LAGO Innovation Fund](https://www.lagoinnovation.com), Long Run Capital, JoinForces Ventures, [1121.vc](https://1121.vc)
- Jim O'Neill, Deven Sharma, Ken Rapp, Kashish Mittal, Rikesh Govan, and many more amazing individuals.

*Apologies if we left you off the list. It was almost certainly accidental 🙃.*
