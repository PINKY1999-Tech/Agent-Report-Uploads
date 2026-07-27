# eDiscovery Morning Briefing — July 27, 2026

## Executive Summary

Monday brings four significant developments spanning AI litigation trends, eDiscovery case law, cybersecurity supply chain risk, and EU digital regulation enforcement. Federal civil pro se plaintiff rates rose from 11.33% to 16.94% after widespread generative AI access—roughly 157,080 more filings—creating increased defense costs for insurers. Judge Beeler denied discovery-on-discovery requests over LinkedIn's Relativity aiR use, finding target population size alone doesn't warrant the metrics audit. Swiss train manufacturer Stadler rejected a $12.3 million ransom after attackers exploited stolen credentials on a supplier data-exchange platform—third-party governance implications for legal hold and breach response. And Google faces €890 million in DMA penalties with a 60-day compliance clock, converting ranking fairness into an evidentiary problem. Together, these stories signal expanding pressure on organizations to demonstrate—not just assert—compliance across AI use, vendor governance, and platform fairness.

---

## Lead Story: Pro Se Filings Rise 50% Post-Generative AI

Federal civil pro se plaintiff rates jumped from 11.33% before widespread generative AI access to 16.94% afterward—roughly 157,080 more filings out of 2.8 million federal cases.

### The Challenge

According to analysis in The National Law Review:
- Publicly available AI tools can draft complaints, motions, discovery requests, and briefs in seconds
- Self-represented litigants can submit documents that look sophisticated even when legal analysis is weak, inaccurate, or fabricated
- Unlike attorneys, pro se litigants generally receive no formal training on AI risks, verification standards, or duty of candor

### Defense Cost Implications

For insurers and legal operations:
- AI-generated filings may appear credible but still require careful review, response, and court appearances
- AI-consistent complaints were more citation-dense and more likely to be dismissed earlier—but still produce defense costs despite lack of merit
- The New Jersey Supreme Court's guidance warns lawyers to verify AI output; the concern applies with greater force when no lawyer is involved

### The Hallucination Count

As of early July, pro se filings were responsible for "only" 1,018 AI hallucinations case filings—suggesting the volume increase hasn't proportionally increased fabricated citations in court.

### Key Question

> "We spend so much time talking about lawyers' misuse of AI, but not near enough about the increased filings—and corresponding misuse of AI—by pro se parties. This is an even bigger challenge in the court system." — Doug Austin, eDiscovery Today

---

## Case Law: Discovery-on-Discovery Over Relativity aiR Denied

Judge Laurel Beeler (N.D. Cal.) denied plaintiffs' requests for metrics on LinkedIn's Relativity aiR use in *Schulte v. LinkedIn Corp.*

### What Plaintiffs Requested

1. Prohibit LinkedIn from using search strings to pre-cull documents reviewed by Relativity aiR
2. Compel LinkedIn to use Relativity aiR across all custodial files
3. Compel LinkedIn to disclose metrics: elusion estimates, document error rate, number of human reviewers validating predictions

### What LinkedIn Argued

- Its use of search strings satisfied the Interim ESI Order
- It disclosed Relativity aiR use on May 15, 2026
- Applying aiR to all custodial files without search strings would be disproportionate—two custodians alone total ~800 GB; 19 custodians would require multiple terabytes

### The Ruling

Judge Beeler denied plaintiffs' requests:

> "The plaintiffs have not shown that LinkedIn's twenty-five search strings are deficient... If the plaintiffs had shown that LinkedIn's search strings were too narrow, their concern about pre-culling might be warranted. But they have not made that argument."

On discovery-on-discovery:

> "As a general matter, discovery of another party's evidence preservation and collection efforts—or 'discovery on discovery'—is disfavored... Such discovery may be warranted if the party requesting it demonstrates that there is a specific deficiency... but 'mere speculation' is insufficient."

The key finding: "The number of documents in the target population alone does not warrant the requested discovery on discovery."

Judge Beeler ordered parties to meet-and-confer on search strings, with relief available if agreement cannot be reached.

---

## Cybersecurity: Stadler Rejects $12.3M Ransom After Supplier Platform Breach

Swiss train manufacturer Stadler Rail refused a 10 million Swiss franc ($12.3M) ransom after attackers exploited stolen credentials to access a data-exchange platform shared with a supplier.

### The Incident

- Attackers used compromised credentials—not a breached firewall—to reach the platform
- Stole technical files belonging to the supplier (not Stadler)
- Stadler stated: no safety-relevant data, no personal data, production and in-service vehicles untouched
- Group calling itself Everest demanded payment; Stadler refused and filed criminal complaint with Thurgau cantonal police

### The Third-Party Governance Story

The incident centered on a file-exchange platform between two companies. Verizon's 2026 DBIR found:
- Third-party involvement appeared in 48% of breaches—up 60% from prior dataset
- Credential abuse accounted for 13% of known initial-access vectors

### Key Questions Unresolved

- Who ran the platform?
- Whose credentials were compromised?
- Who owes regulatory notification?

Stadler's statement doesn't settle these. The ambiguity decides who owns the logs, who owns notification duty, and who answers the first subpoena.

### Legal Hold Implications

If litigation or enforcement is reasonably anticipated, preservation may extend to records held in supplier-hosted repositories. Legal teams should know:
- Which supplier-hosted repositories hold company work product
- What retention terms say
- Whether the supplier can preserve on request
- How quickly it can export

---

## EU Enforcement: Google's €890M DMA Penalty Package

The European Commission fined Google €890 million across two Digital Markets Act decisions and required compliance within 60 days.

### The Two Decisions

1. **€460 million for self-preferencing on Google Search**: Commission found Google "gives preferential treatment to its own services, including shopping, hotels, transport and sports results, over those of third parties"
2. **€430 million for anti-steering on Google Play**: Commission found Google "prevents app developers from freely communicating and promoting offers and concluding contracts with users"

### The 60-Day Clock

If Google doesn't comply within 60 days, periodic penalty payments up to 5% of daily worldwide turnover could apply—roughly $55 million per day against Alphabet's fiscal 2025 revenue of $402.8 billion (statutory maximum, not automatic).

### The Evidentiary Shift

Article 6(5) requires gatekeepers to "apply transparent, fair and non-discriminatory conditions to such ranking." That's an evidentiary standard wearing the clothes of a design rule.

The Commission's findings examined placement, visual treatment, and filter availability—all observable externally. Demonstrating non-discrimination from the inside requires:
- Versioned ranking configurations
- Experiment records behind layout decisions
- Documented rationale for why surfaces treat first-party and third-party results differently

### The Retention Order

On March 25, 2024, the Commission ordered five gatekeepers (Alphabet, Amazon, Apple, Meta, Microsoft) to retain documents bearing on DMA compliance. Product configurations, testing records, compliance correspondence, and technical materials became potential regulatory evidence.

### AI Overviews in the Perimeter

The Commission noted it "takes note of Google's proposals on how it plans to apply the principles of the decision to AI Overviews and AI Mode." Generated answer surfaces are now inside the ranking-fairness conversation.

---

## Key Dates Tracker

| Milestone | Date | Days Remaining |
|-----------|------|----------------|
| EDRM 2.0 public comment closes | July 30, 2026 | 3 days |
| EU AI Act Article 50 (transparency) | Aug 2, 2026 | 6 days |
| Google DMA 60-day compliance deadline | ~Sept. 21, 2026 | ~56 days |
| EU Article 5 nudifier ban | Dec 2, 2026 | ~4 months |
| EU AI Act Annex III high-risk | Dec 2, 2027 | ~17 months |

---

## What to Watch

1. **Pro se AI filings**: 157,080 more federal filings—defense cost center for insurers
2. **Discovery-on-discovery limits**: Target population size alone doesn't warrant metrics audit
3. **Third-party platform risk**: Credential abuse on supplier platforms—legal hold implications
4. **DMA evidentiary burden**: Ranking fairness now requires demonstration from retained records
5. **AI surfaces in scope**: Generated answer surfaces entering compliance perimeter

---

## Sources

- eDiscovery Today: Pro se AI filings, Relativity aiR case law
- The National Law Review: AI-assisted pro se litigation analysis
- ComplexDiscovery: Stadler breach, Google DMA penalty
- European Commission: DMA enforcement announcement
- Verizon DBIR 2026: Third-party breach statistics

---

*Generated: July 27, 2026 — Monday briefing, AI litigation surge and enforcement pressure*