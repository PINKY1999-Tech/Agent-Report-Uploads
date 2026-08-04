# eDiscovery Morning Briefing — August 4, 2026

## Executive Summary

Tuesday brings AI governance and evidence integrity to the fore. Suffolk Law Dean Andrew Perlman's new site catalogs AI policies at 128 law schools—an AI-assembled archive documenting how law schools regulate AI. Doug Austin covers privacy controls for public AI chatbots: all major models train on your data by default, and even Claude's "Share" feature exposed sensitive content in Google search. ComplexDiscovery's analysis of wartime reporting from Russia offers a case study in euphemism-as-record, escalation bias, and AI-generated battlefield footage—a governance lesson applicable to incident reporting everywhere. Together, these signal AI transparency obligations meeting privacy risks, and record integrity challenges that cross from war zones to compliance reviews.

---

## Lead Story: 128 Law School AI Policies Cataloged

Dean Andrew Perlman (Suffolk Law) has launched an AI policy archive for legal education.

### The Resource

- **Site**: AI in Legal Education: Law School Policy Archive
- **Coverage**: AI policies from 128 of 196 U.S. law schools
- **Organization**: Eight topic areas
- **Sources**: Student handbooks, honor codes, dean's memoranda, strategy statements, program pages
- **Status labels**: In effect, interim, pilot, proposed, guidance, completed/limited

### How It Was Built

ChatGPT Sites was used extensively:
- Locating public sources
- Organizing into topic categories
- Helping draft summaries

Perlman has not manually reviewed or independently confirmed every reference.

### The Irony

> "It is, in other words, an AI-assembled archive documenting how law schools regulate AI."

### Key Finding: Mandatory AI Instruction Spreading

Bob Ambrogi's analysis (using Claude to evaluate ChatGPT's work):
- **26 schools** have mandatory AI curriculum or literacy requirements
- List is "growing semester by semester"

### The University of Chicago Example

The archive references Chicago's "2026–27 pilot [which] pairs device-free classrooms across all core 1L sections"—prohibiting electronic devices for first-year students.

### The Governance Question

A site built by AI cataloging AI policies is bound to have errors. The question: will schools ensure their information is complete and accurate?

---

## Privacy Controls for Public AI Chatbots

Doug Austin covers practical steps for keeping AI conversations private.

### The Default Problem

**All major models train on your content by default:**
- ChatGPT
- Google Gemini
- Microsoft Copilot
- Claude

Even Claude—which previously did not train by default—now sets training to "on" during account setup.

### Privacy Methods by Platform

Each platform offers five methods:

1. **Use without an account** (ChatGPT) — fewer features, lower thresholds
2. **Disable training** — available in all models, must be actively turned off
3. **Temporary/incognito mode** — for specific sensitive conversations
4. **Delete conversations** — doesn't remove training if already enabled
5. **Control service connections** (Copilot) — OneDrive, Outlook, Google Drive, Gmail, Calendar

### The Share Feature Risk

Claude's "Share" feature:
- Generates public links
- "Anyone with the link can view"
- Content was being indexed by search engines
- Medical reports, clinical trial data, children's contact details exposed in Google results
- Anthropic "quickly fixed the 'exploit'"
- Doesn't help those already exposed

### The Core Lesson

> "It's probably safest to assume that [all models] train on your content by default."

---

## Wartime Reporting as Governance Case Study

ComplexDiscovery's analysis of Russian battlefield reporting offers lessons for records professionals everywhere.

### Three Claims, One Morning, No Reconciliation

Omsk refinery, Aug. 2:
1. Footage "reportedly showed smoke" from refinery
2. Governor: drone debris caused fire in "field near Omsk City"
3. Milblogger: Ukrainian drones "did not reach the refinery at all"

The Institute for the Study of War relayed all three without reconciling them.

### The Euphemism Problem

Russian officials' construction:
- "Drone debris caused a fire"
- "Air defenses turned back a major drone attack"
- Something fell, something burned, nobody struck anything

The phrasing is policy, not description. A euphemism repeated across enough reports stops being a word choice and becomes the data.

### The Governance Lesson

> "Incident reports that say 'service degradation' when they mean 'intrusion' produce trend analysis measuring vocabulary rather than risk."

**The corrective**: Audit the language of your incident record against the underlying artifacts on a sample basis.

### Escalation Bias

ISW assessed that Russian commanders "are likely lying to the Kremlin about the extent of Russian gains" to advance the narrative of progress.

Consequences documented by pro-war bloggers:
- Countermeasures based on false picture
- Coordination failures
- Casualties in the hundreds

### The Lesson

> "A reporting chain that rewards the answer leadership wants will supply that answer, and the damage does not arrive as an obvious lie. It arrives as resource allocation built on a map that no longer matches the ground."

### AI-Generated "Proof"

July 27: Russian sources circulated video purporting to show a flag-raising at Bilyi Kolodyaz.
- ISW assessed the footage was "likely generated or altered using artificial intelligence"
- Indicators: soldier vanished mid-clip, shadows didn't match
- GeoConfirmed identified the manipulation

---

## Key Dates Tracker

| Milestone | Date | Status |
|-----------|------|--------|
| EU AI Act Article 50 | Aug 3, 2026 | IN EFFECT |
| NY water sector compliance | Jan. 1, 2027 | ~5 months |
| Google DMA 60-day deadline | ~Sept. 21, 2026 | ~48 days |
| EU Article 5 nudifier ban | Dec 2, 2026 | ~4 months |

---

## What to Watch

1. **Law school AI policies**: 26 schools with mandatory AI curriculum
2. **AI chatbot privacy**: Training defaults, share feature risks
3. **Incident report language**: Euphemism-as-record governance failures
4. **Escalation bias**: Reporting chains optimized for expected answers
5. **AI-generated evidence**: Visual manipulation in evidentiary contexts

---

## Sources

- eDiscovery Today: Law school AI policies, chatbot privacy
- ComplexDiscovery: Wartime reporting analysis
- LawSites: Bob Ambrogi's analysis
- ZDNet: Lance Whitney's privacy guide

---

*Generated: August 4, 2026 — Tuesday briefing, law school AI policies, chatbot privacy, wartime reporting governance*