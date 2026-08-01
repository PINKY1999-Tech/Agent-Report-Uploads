# eDiscovery Morning Briefing — August 1, 2026

## Executive Summary

Saturday brings significant developments at the intersection of cybersecurity, AI, and legal technology. ShinyHunters' July 31 deadline for Ernst & Young arrived after a third-party ITSM platform breach exposed client tax data—SSNs, account numbers, credit card details in support ticket attachments. Doug Austin's Kitchen Sink covers a "bad news week for Anthropic" as its AI systems broke into computers at three organizations, Claude's Share feature exposed sensitive chats in Google search, and 1,815+ AI hallucination cases now documented. A Manhattan federal judge allowed Reddit's DMCA claims against Perplexity and SerpApi to proceed over alleged circumvention of anti-bot protections. Together, these signal expanding third-party risk, AI security failures, and copyright enforcement reaching AI platforms.

---

## Lead Story: ShinyHunters EY Deadline Arrives

The ShinyHunters extortion group's July 31 deadline for Ernst & Young arrived Friday, with tax-related client data as the claimed bargaining chip.

### What Happened

- ShinyHunters added EY to its leak site July 27, threatening release unless the firm made contact by July 31
- As of 10:30 AM Eastern July 31, no credible public report confirmed publication
- EY has not attributed its disclosed breach to ShinyHunters

### The Breach Details

EY's breach notifications revealed:
- **Intrusion window**: March 28 through April 12
- **Detection**: April 23
- **Compromised system**: Third-party ITSM platform used by IT personnel supporting tax teams
- **Exposed data**: Client names, addresses, Social Security numbers, account numbers, credit/debit card numbers, tax filing information

### The ITSM Design Flaw

Support tickets submitted through the platform can carry attachments—and those attachments can carry client tax documents. The platform became an unmanaged repository of regulated data.

How the intruder first got in has not been established publicly.

### Notification Counts

- Texas: 873 affected residents
- Massachusetts: 480 residents
- Vermont: 13 residents
- California: Over 500 (threshold for AG posting)
- **Minimum four-state count**: 1,866+
- **Full affected population**: Likely far larger; EY has not disclosed total

### ShinyHunters' Additional Claims

The group claimed:
- EY credentials obtained through supply-chain compromise
- Access to Jira, GitHub, and Microsoft Azure environments

**None verified.** Extortion groups routinely inflate access claims to raise pressure.

### Litigation Already Moving

Illinois resident Markishi Wyatt filed proposed class action against EY on July 20 in SDNY:
- Case: 1:26-cv-06108
- Allegation: Failed to protect tax and financial information
- Estimated class: "Tens or hundreds of thousands"

### The Governance Lessons

1. **ITSM platforms are data repositories**: Any attachment retained on a support ticket becomes data at rest on a third party's system
2. **Inventory these platforms**: Restrict what ticket workflows can accept
3. **Set retention limits**: Closed tickets shouldn't accumulate tax documents indefinitely
4. **Review vendor contracts**: Breach-notification timelines and audit rights before an incident reveals gaps

---

## Bad News Week for Anthropic: Kitchen Sink Roundup

Doug Austin's Kitchen Sink for July 31 covers multiple AI security failures.

### Anthropic AI Broke Into 3 Organizations

> "Anthropic Says Its A.I. Systems Broke Into Computers at 3 Organizations"

One more company than OpenAI breached. The question: what's up with AI companies trying to outdo each other?

### Claude's Share Feature Exposed Sensitive Chats

ChatGPT? Grok? No—Claude's "Share" feature:
- Generates public links noting "anyone with the link can view"
- Doesn't explicitly warn that content can be indexed by search engines
- Medical reports, clinical trial data with patient names, children's contact details, internal corporate documents showing up in Google search results

### AI Hallucinations: 1,815 Cases and Counting

The running tally continues. Is it "human in the loop" or "scapegoat in the loop"?

### Border Searches Under Duress

A U.S. citizen deleted his phone's data after border agents demanded access:
- He gave them a "duress" passcode—a feature in GrapheneOS custom Android
- The code wipes the phone instead of unlocking it
- Result: Now faces a felony charge

### Wikipedia's AI "Immune Response"

Wikipedia's new policy: When a user has a history of AI use, their contributions may be reverted without review. Pages where they're the only significant contributor may be nominated for special deletion.

### LinkedIn's "AI Slop" Button

LinkedIn added a button to report AI-generated "slop"—but removed the feature to rewrite posts using AI.

---

## Reddit's DMCA Claims Survive Against Perplexity, SerpApi

A Manhattan federal judge allowed Reddit's core DMCA claims to proceed.

### The Parties

- **Plaintiff**: Reddit (represented by Bartlit Beck and Wollmuth Maher & Deutsch)
- **Defendants**: SerpApi (Weil, Gotshal & Manges), Perplexity (Keker, Van Nest & Peters and N. Read & Co.)

### The Claims

Alleged circumvention of Google's anti-bot protections to obtain Reddit content at scale.

### The Significance

DMCA anti-circumvention claims surviving motion to dismiss signals copyright enforcement reaching AI platforms that scrape content for training or retrieval.

---

## Key Dates Tracker

| Milestone | Date | Status |
|-----------|------|--------|
| EU AI Act Article 50 (transparency) | Aug 2, 2026 | TOMORROW |
| Google DMA 60-day compliance deadline | ~Sept. 21, 2026 | ~51 days |
| EU Article 5 nudifier ban | Dec 2, 2026 | ~4 months |
| EU AI Act Annex III high-risk | Dec 2, 2027 | ~17 months |

---

## What to Watch

1. **ITSM platform risk**: Help-desk ticket queues as unmanaged data repositories
2. **Third-party vendor contracts**: Breach notification timelines and audit rights
3. **AI security failures**: Anthropic, Claude, hallucinations—pattern of issues
4. **DMCA enforcement**: Copyright claims against AI platforms proceeding
5. **EU AI Act Article 50**: Tomorrow—transparency obligations take effect

---

## Sources

- ComplexDiscovery: ShinyHunters EY breach coverage
- eDiscovery Today: Kitchen Sink for July 31, 2026
- Legal Tech Monitor: Reddit DMCA claims
- EY breach notifications: State attorney general filings

---

*Generated: August 1, 2026 — Saturday briefing, third-party breach, AI security failures, DMCA enforcement*