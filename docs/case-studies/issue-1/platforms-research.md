# Online Earning Platforms Research Data

## Criteria for Evaluation

1. **Low entry barrier** - no need to build profile or self-promote to get paid tasks
2. **AI-compatible tasks** - tasks that [hive-mind](https://github.com/link-assistant/hive-mind) (autonomous AI issue solver based on Claude) can handle
3. **No payment issues in Russia (RF territory)** - crypto payments preferred
4. **Low risk of not getting paid** for completed work

## Hive-Mind Capabilities

Hive-mind is an AI orchestration system that:
- Automatically solves GitHub issues
- Writes code across multiple programming languages
- Creates pull requests
- Performs code reviews
- Monitors repositories for new issues
- Handles file operations in repositories
- Can do "almost anything that can be done with files in a repository"

---

## Category 1: GitHub-Based Bounty Platforms

### 1.1 Algora
- **URL**: https://algora.io
- **How it works**: Fund GitHub issues with USD bounties. Developers solve issues, submit PRs, get paid when merged. Command `/bounty $AMOUNT` creates bounties directly in GitHub issues.
- **Entry barrier**: Low. Sign up with GitHub, browse bounties, submit PRs.
- **Payment**: USD via Stripe. No crypto confirmed.
- **AI compatibility**: HIGH. Direct GitHub integration. Hive-mind can solve issues and submit PRs automatically.
- **Risk level**: Low - payment on merge.
- **Russia/RF notes**: Stripe may have restrictions for Russian accounts. Needs intermediary.

### 1.2 BountyHub
- **URL**: https://www.bountyhub.dev
- **How it works**: Paste GitHub Issue URL, set bounty amount. Developers submit PRs, bounty creator reviews and approves. 10% fee on top of bounty.
- **Entry barrier**: Low. GitHub-integrated.
- **Payment**: Stripe or PayPal.
- **AI compatibility**: HIGH. Direct GitHub workflow.
- **Risk level**: Low-Medium - dispute resolution available.
- **Russia/RF notes**: PayPal restricted in Russia. Stripe may have issues.

### 1.3 IssueHunt
- **URL**: https://oss.issuehunt.io
- **How it works**: Issue-based bounty platform for open source. Anyone can fund bounties on GitHub issues. Contributors get rewards after PR is accepted.
- **Entry barrier**: Low. GitHub integration.
- **Payment**: Cryptocurrency and traditional currency options.
- **AI compatibility**: HIGH. Standard GitHub workflow.
- **Risk level**: Low - established platform.
- **Russia/RF notes**: Crypto option may work.

### 1.4 Opire
- **URL**: https://opire.dev
- **How it works**: Bounties on any GitHub issue. Claim bounty, solve issue, create PR. Developer gets 100% of rewards. Multiple sponsors can fund one bounty. 4% fee.
- **Entry barrier**: Very Low. Minimal setup, direct GitHub integration via OpireBot.
- **Payment**: Payment on PR merge.
- **AI compatibility**: HIGH. Direct GitHub integration.
- **Risk level**: Low - automated via bot.
- **Russia/RF notes**: Payment method details need verification.

### 1.5 Gitpay
- **URL**: https://gitpay.me
- **How it works**: Open source bounty platform. Apply to work on issues, get approved, submit code. Payment sent when code is merged.
- **Entry barrier**: Low. Standard GitHub workflow.
- **Payment**: Credit card based, bank account needed.
- **AI compatibility**: HIGH. Git-based workflow.
- **Risk level**: Low - payment on merge.
- **Russia/RF notes**: Bank account requirements may be problematic.

### 1.6 Boss Bounty (boss.dev)
- **URL**: https://www.boss.dev / https://github.com/marketplace/boss-bounty
- **How it works**: GitHub app. Attach bounties to issues. Money transferred automatically when issue closed by commit/PR. 33 international currencies.
- **Entry barrier**: Very Low. One visit to boss.dev to setup, then everything happens in GitHub.
- **Payment**: Automatic bank transfer.
- **AI compatibility**: HIGH. Pure GitHub workflow.
- **Risk level**: Low - automated payment.
- **Russia/RF notes**: Bank transfer availability for Russia unclear.

---

## Category 2: Crypto/Web3 Bug Bounty Platforms

### 2.1 Immunefi
- **URL**: https://immunefi.com
- **How it works**: Web3 bug bounty platform. Review smart contract code, find vulnerabilities, submit reports. Paid out $100M+ total. Bounties from $1K to $15M.
- **Entry barrier**: Medium. Need security knowledge. KYC required for payouts.
- **Payment**: Crypto only - USDC, SOL, project-specific tokens.
- **AI compatibility**: MEDIUM. Requires deep smart contract security analysis. Hive-mind could potentially find code issues but needs specialized prompting.
- **Risk level**: Low - well-established, crypto escrow.
- **Russia/RF notes**: Crypto payments work globally. KYC may be an issue for sanctioned individuals but platform is international.

### 2.2 HackenProof
- **URL**: https://hackenproof.com
- **How it works**: Web3 bug bounty platform. 308+ active programs. Bounties up to $300K. Find vulnerabilities, submit reports.
- **Entry barrier**: Low-Medium. Sign up, start hunting. KYC may be optional depending on program.
- **Payment**: USDC (Base network), BTC, or ETH. Minimum withdrawal $100.
- **AI compatibility**: MEDIUM. Smart contract and web3 security focused.
- **Risk level**: Low - established platform.
- **Russia/RF notes**: Crypto payouts (BTC, ETH, USDC) should work internationally.

### 2.3 Code4rena
- **URL**: https://code4rena.com
- **How it works**: Competitive smart contract audit contests. Time-bound audits with prize pools. Everyone who submits valid bug gets paid (not just first finder). Shares system for reward distribution.
- **Entry barrier**: Medium. Need smart contract audit skills. Application process required.
- **Payment**: Crypto (specific tokens depend on sponsor).
- **AI compatibility**: MEDIUM-HIGH. Code review/audit is within hive-mind capabilities, but requires Solidity/smart contract expertise.
- **Risk level**: Very Low - everyone with valid finding gets paid.
- **Russia/RF notes**: Crypto payments favorable for RF.

### 2.4 Sherlock
- **URL**: https://sherlock.xyz
- **How it works**: Competitive smart contract audits. Open, time-boxed review contests. Major contests like $2M Ethereum Fusaka audit. Senior "Watson" experts on each audit.
- **Entry barrier**: Medium-High. Requires strong smart contract security skills.
- **Payment**: Crypto.
- **AI compatibility**: MEDIUM. Requires deep security audit expertise.
- **Risk level**: Very Low - structured rewards, up to $2M insurance coverage.
- **Russia/RF notes**: Crypto payments favorable.

### 2.5 Cantina
- **URL**: https://cantina.xyz
- **How it works**: Security competitions and bounties for smart contracts. Major sponsors (Ethereum Foundation, Coinbase, Morpho). Competitions with large prize pools ($1M+).
- **Entry barrier**: Medium-High. Professional security review skills needed.
- **Payment**: Crypto.
- **AI compatibility**: MEDIUM. Code review capability present but needs security specialization.
- **Risk level**: Low - major corporate sponsors.
- **Russia/RF notes**: Crypto payments favorable.

---

## Category 3: General Bug Bounty Platforms

### 3.1 HackerOne
- **URL**: https://www.hackerone.com
- **How it works**: Largest bug bounty platform. $300M+ paid total. Find vulnerabilities in web apps, APIs, mobile apps. Submit reports, get paid after validation.
- **Entry barrier**: Low-Medium. Sign up free, start hunting on public programs.
- **Payment**: PayPal, bank transfer, Bitcoin (on select programs).
- **AI compatibility**: LOW-MEDIUM. More about web/infrastructure security than code. Hive-mind better suited for code-level bugs.
- **Risk level**: Very Low - industry standard, well-established.
- **Russia/RF notes**: Bitcoin option on some programs. PayPal restricted in Russia. Bank transfer may be complicated.

### 3.2 Bugcrowd
- **URL**: https://bugcrowd.com
- **How it works**: Bug bounty platform. Security testing programs from major companies. Find vulnerabilities, report, get paid.
- **Entry barrier**: Low-Medium. Open registration.
- **Payment**: Bank transfer, PayPal, Bitcoin (on select programs).
- **AI compatibility**: LOW-MEDIUM. Similar to HackerOne.
- **Risk level**: Low - established platform.
- **Russia/RF notes**: Bitcoin available on select programs.

### 3.3 Intigriti
- **URL**: https://www.intigriti.com
- **How it works**: European-focused bug bounty platform. 125K+ researchers. Public and private programs.
- **Entry barrier**: Low-Medium.
- **Payment**: Wire transfer, PayPal, Payoneer. NO crypto.
- **AI compatibility**: LOW-MEDIUM.
- **Risk level**: Low - established European platform.
- **Russia/RF notes**: No crypto. Wire transfer and Payoneer may have restrictions.

---

## Category 4: Crypto Freelance Platforms

### 4.1 LaborX
- **URL**: https://laborx.com
- **How it works**: Blockchain-based freelance marketplace. Post/find jobs, apply, complete work. Smart contract escrow secures payments.
- **Entry barrier**: Low. Connect wallet, browse jobs.
- **Payment**: Ethereum, BSC, TRON, Polygon tokens. 10% freelancer commission.
- **AI compatibility**: MEDIUM. General dev tasks available but need to apply for each job.
- **Risk level**: Low - smart contract escrow.
- **Russia/RF notes**: EXCELLENT. Crypto-native, no geography restrictions. Multiple blockchain networks.

### 4.2 CryptoTask
- **URL**: https://www.cryptotask.org
- **How it works**: Decentralized freelance marketplace on Ethereum. 0% fees for freelancers. 20K+ freelancers. Escrow-based disputes.
- **Entry barrier**: Very Low. 0% fees, blockchain-based reputation.
- **Payment**: Choose any cryptocurrency. Smart contract escrow.
- **AI compatibility**: MEDIUM. General tasks, need to apply individually.
- **Risk level**: Low - escrow system.
- **Russia/RF notes**: EXCELLENT. Fully decentralized, no geographic restrictions.

### 4.3 HYVE
- **URL**: https://www.hyve.works
- **How it works**: Web3 freelance marketplace. Accept 200+ cryptocurrencies. Low fees.
- **Entry barrier**: Low.
- **Payment**: 200+ cryptocurrencies.
- **AI compatibility**: MEDIUM. General freelance tasks.
- **Risk level**: Low.
- **Russia/RF notes**: GOOD. Wide crypto support.

### 4.4 Dework
- **URL**: https://dework.xyz
- **How it works**: Task manager for DAOs. 500+ DAOs posting bounties and grants. Connect Discord/wallet/GitHub. Build reputation through completed bounties (Developer levels 1-3).
- **Entry barrier**: Low. Connect wallet and GitHub, browse bounties.
- **Payment**: Token payments from DAOs.
- **AI compatibility**: MEDIUM-HIGH. Many developer bounties for code tasks.
- **Risk level**: Low-Medium - depends on specific DAO.
- **Russia/RF notes**: GOOD. Crypto-native, wallet-based.

### 4.5 Bountycaster
- **URL**: https://www.bountycaster.xyz
- **How it works**: Crypto bounty platform on Farcaster social protocol. $1.5M in bounties posted across 2,922 bounties. No fees. Peer-to-peer payments.
- **Entry barrier**: Low. Create Farcaster account (free), browse bounties.
- **Payment**: USDC, ETH, DEGEN, OP tokens on Base. Zero fees.
- **AI compatibility**: MEDIUM. Various tasks including development.
- **Risk level**: Low - peer-to-peer, no middleman fees.
- **Russia/RF notes**: GOOD. Crypto-native.

---

## Category 5: Crypto/Web3 Developer Bounties

### 5.1 Gitcoin
- **URL**: https://gitcoin.co
- **How it works**: Open source bounties paid in crypto. $60M+ distributed. Issue Explorer for bounties in Python, JS, Rust, Solidity, etc. Bounties range $1.5K-$50K. Also runs Grants rounds (quadratic funding).
- **Entry barrier**: Low. Connect wallet, browse bounties.
- **Payment**: ETH and ERC-20 tokens.
- **AI compatibility**: HIGH. Open source code bounties directly aligned with hive-mind capabilities.
- **Risk level**: Low - long-established, major web3 platform.
- **Russia/RF notes**: EXCELLENT. Crypto-native, Ethereum-based, no geographic restrictions.

---

## Category 6: AI Training / Data Annotation Platforms

### 6.1 Outlier AI (Scale AI subsidiary)
- **URL**: https://outlier.ai
- **How it works**: Data annotation, coding task evaluation, AI training. Check accuracy of AI code, debug, review responses. Weekly payments.
- **Entry barrier**: Low-Medium. Application and onboarding required.
- **Payment**: PayPal, AirTM. $15-$60/hr depending on expertise.
- **AI compatibility**: LOW. Tasks often require human judgment about AI quality.
- **Risk level**: Low - Scale AI backed.
- **Russia/RF notes**: PayPal restricted. AirTM may work.

### 6.2 Mindrift
- **URL**: https://mindrift.ai
- **How it works**: AI training platform. Writing, editing, annotation tasks. $20-$55/hr. Bi-weekly payments. 20K+ AI Trainers.
- **Entry barrier**: Medium. Application process, quality review.
- **Payment**: "Trusted online payment platforms" - bi-weekly.
- **AI compatibility**: LOW. Human evaluation of AI quality.
- **Risk level**: Low - established platform.
- **Russia/RF notes**: Payment methods need verification.

### 6.3 CrowdGen (Appen)
- **URL**: https://crowdgen.com
- **How it works**: Data annotation, transcription, translation, content moderation. Pay per task, up to $40/hr.
- **Entry barrier**: Low. Various task types available.
- **Payment**: PayPal, Payoneer, bank transfer, Airtm, e-wallet.
- **AI compatibility**: LOW. Designed for human evaluation tasks.
- **Risk level**: Low - Appen is a public company.
- **Russia/RF notes**: Payoneer and Airtm may work. PayPal restricted.

### 6.4 Toloka (ex-Yandex)
- **URL**: https://toloka.yandex.com
- **How it works**: Microtask/crowdsourcing platform. Data labeling, surveys, content evaluation. $0.02 minimum cashout. ~$1-3/hr.
- **Entry barrier**: Very Low. Simple signup, immediate task access.
- **Payment**: PayPal, Yandex.Money, bank transfer.
- **AI compatibility**: LOW. Simple tasks not suitable for AI system.
- **Risk level**: Very Low - Yandex-backed.
- **Russia/RF notes**: EXCELLENT. Yandex.Money native support. Russian company origin.

---

## Category 7: Micro-Task Platforms with Crypto

### 7.1 JumpTask
- **URL**: https://jumptask.io
- **How it works**: Micro-tasks (surveys, app downloads, video watching) paid in crypto. TaskFi model on BSC.
- **Entry barrier**: Very Low.
- **Payment**: JumpToken (JMPT) on BSC.
- **AI compatibility**: VERY LOW. Simple human tasks.
- **Risk level**: Low.
- **Russia/RF notes**: Crypto payout, BSC-based.

### 7.2 Click For Crypto
- **URL**: https://www.clickforcrypto.com
- **How it works**: Micro-tasks paid in USDT. Instant payment on approval. $0.01-$10+ per task.
- **Entry barrier**: Very Low.
- **Payment**: USDT.
- **AI compatibility**: VERY LOW. Human micro-tasks.
- **Risk level**: Low-Medium.
- **Russia/RF notes**: USDT payout works internationally.

---

## Russia/RF Crypto Landscape (2025-2026)

### Key Facts:
- Russia is Europe's largest crypto market: $376B annual transaction volume (2026)
- Central bank legalizing crypto trading for individuals and institutions
- Legislation expected complete by July 1, 2026
- Non-qualified investors: max 300,000 rubles/year per intermediary
- Crypto cannot be used for domestic payments (but can be bought/sold)
- Sberbank preparing crypto-backed lending
- Popular exchanges in Russia: BingX, Bitget, others
- Stablecoins (USDT, USDC) widely used for international settlements
- P2P crypto trading active

### Payment Methods That Work in Russia:
1. **Cryptocurrency** (USDT, USDC, BTC, ETH) - Best option
2. **Payoneer** - Generally accessible
3. **Airtm** - Generally accessible
4. **Yandex.Money** - Native Russian payment
5. **Wire transfer** - May have SWIFT restrictions
6. **PayPal** - Restricted/unavailable
7. **Stripe** - Restricted

---

## Sources

- Immunefi: https://immunefi.com
- HackenProof: https://hackenproof.com
- Code4rena: https://code4rena.com
- Sherlock: https://sherlock.xyz
- Cantina: https://cantina.xyz
- HackerOne: https://www.hackerone.com
- Bugcrowd: https://bugcrowd.com
- Intigriti: https://www.intigriti.com
- Algora: https://algora.io
- BountyHub: https://www.bountyhub.dev
- IssueHunt: https://oss.issuehunt.io
- Opire: https://opire.dev
- Gitpay: https://gitpay.me
- Boss Bounty: https://www.boss.dev
- Gitcoin: https://gitcoin.co
- LaborX: https://laborx.com
- CryptoTask: https://www.cryptotask.org
- HYVE: https://www.hyve.works
- Dework: https://dework.xyz
- Bountycaster: https://www.bountycaster.xyz
- Outlier AI: https://outlier.ai
- Mindrift: https://mindrift.ai
- CrowdGen: https://crowdgen.com
- Toloka: https://toloka.yandex.com
- JumpTask: https://jumptask.io
- Click For Crypto: https://www.clickforcrypto.com
