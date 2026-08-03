# eDiscovery Morning Briefing — August 3, 2026

## Executive Summary

Monday brings critical infrastructure security and evidence preservation questions to the fore. Federal water sector guidance tells utilities how to restore locked PLCs—but remains silent on preserving controller evidence before recovery. Minnesota counted 30+ community water systems targeted in 48 hours, and the recovery path for Rockwell MicroLogix devices (clearing memory) destroys the running program. Brad Blickstein's new book applies private equity thinking to law firms: professionalize pricing, treat technology as enterprise value, and address the COO authority gap. Level Legal's "Five eDiscovery Decisions" framework emphasizes competence as a required legal skill. Today, **EU AI Act Article 50 takes effect**—transparency obligations for generative AI systems now apply.

---

## Lead Story: Water Sector Attacks Raise Preservation Questions

Federal guidance for water utilities facing PLC lockouts tells them how to restore—but not how to preserve evidence.

### The Attack Pattern

- **30+ Minnesota community water systems** targeted in 48 hours (July 26-27)
- **7+ states** reported incidents to FBI since July 27
- Attackers targeted **internet-exposed Rockwell MicroLogix 1100 and 1400 controllers**
- Changed PLC passwords to lock operators out
- Altered IP addresses to cut devices from monitoring networks
- Some organizations found modified PLC project files with ladder logic discrepancies

### The Four Cities That Disclosed

- **Braham, MN**: Plant offline ~90 minutes, restored from backup
- **South St. Paul**: Shifted to manual operation
- **Plymouth**: Lost cellular communications to water towers and lift stations
- **Maple Plain**: Maintained operations, declared local emergency

No boil-water notices issued. No unsafe drinking water reported.

### The Evidence Problem

For Rockwell MicroLogix devices, the manufacturer's manuals document **no password bypass**:
- Recovery path: clearing controller memory
- Result: removes the running program
- What's lost: attacker-set password, altered IP configuration, modified project files, ladder logic changes

**Federal guidance does not tell operators to preserve the compromised state before restoring.**

### The Preservation Gap

What documents tell operators:
- Keep known-clean backups of PLC images
- Verify backups are free of malicious logic before deploying
- Review project files for unauthorized changes
- Review logs and configurations on connected devices

What none of them say:
- Capture the running project or configuration first
- When doing so is safe and feasible
- Who should document controller state before recovery

### The Practical Response

ComplexDiscovery recommends:

1. **Inventory cellular connections into OT now** — ask integrators and vendors to enumerate what they installed
2. **Extend hold templates to controller images** — project files, HMI exports, modem logs, carrier records
3. **Add capture-before-restore step** where safety and technical access allow
4. **Document accessible controller state** — photograph the panel, preserve associated records
5. **Recognize service providers as potential custodians** — integrators may hold key records

### Regulatory Timeline

**New York's water sector cybersecurity regulations** (first in the nation):
- Adopted March 11, 2026
- Drinking water requirements compliance deadline: **Jan. 1, 2027**
- Wastewater requirements phase on separate schedule

---

## Private Equity Thinking for Law Firms

Brad Blickstein's new book *WWPED: What Would Private Equity Do?* challenges law firm leaders to stop treating firms purely as cash-flow vehicles.

### The Cream, Core, Commodity Framework

From Jae Um's market segmentation:

- **Cream (10%)**: High-value, customized legal judgment
- **Core (70%)** — "the ultimate battleground"
- **Commodity (20%)**: Repeatable, scalable work

### The Bakery Analogy

- **Artisanal legal bakery**: Customized judgment, high-touch
- **Crumbl Cookies-style system**: Scalable, consistent, process-driven

Firms must separate customized legal judgment from repeatable processes.

### The COO Authority Gap

2026 Law Firm COO Survey findings:
- **Technology investment/adoption** now #1 strategic initiative (surpassed talent acquisition)
- **38.1%** identified practice silos as largest structural issue
- **27%** cited lack of operational authority

The disconnect: COOs tasked with modernizing firms, but not given authority to overcome decentralized partnerships and competing incentives.

### Pricing Professionalization

Key insight from Blickstein:
- "Faster work in a billable hour model is not the type of math law firms want to calculate"
- Firms need to redesign pricing on **value received by client**, not hours worked
- Professional pricing operation could yield "2-3-5 points across the board"
- Most firms still rely on "partner's gut feeling"

### AI and ROI Measurement

- **Two-thirds of COOs** confessed they were not formally measuring ROI on AI investments
- Firms struggle with AI productivity gains in billable hour models
- Alternative fee arrangements face issues of shadow billing and value expression

---

## Five eDiscovery Decisions That Determine Success

Level Legal's framework emphasizes that most modern cases are won and lost in discovery.

### The Core Premise

> "Making the right decisions during the discovery process will arguably matter more to the success of your case than any other decisions you make... 'I didn't know' is not a defense. The courts have been clear for two decades that competence with ESI is a basic skill required to practice law."

### The Five Decisions

eDiscovery is a sequence of five decisions:
1. Each can advance your case strategically or derail it publicly
2. Associates often bear day-to-day responsibility
3. Responsibilities include running searches, drafting legal holds, coordinating collections, communicating with opposing counsel

### The Field Guide

Level Legal's 29-page *eDiscovery 101: A Field Guide for Associates* covers:
- Checklists for each phase
- Example decision-making scenarios
- How to identify issues to escalate

---

## Key Dates Tracker

| Milestone | Date | Status |
|-----------|------|--------|
| **EU AI Act Article 50 (transparency)** | **Aug 3, 2026** | **TODAY** |
| NY water sector compliance deadline | Jan. 1, 2027 | ~5 months |
| Google DMA 60-day compliance deadline | ~Sept. 21, 2026 | ~49 days |
| EU Article 5 nudifier ban | Dec 2, 2026 | ~4 months |
| EU AI Act Annex III high-risk | Dec 2, 2027 | ~16 months |

---

## What to Watch

1. **EU AI Act Article 50**: TODAY—transparency obligations begin for generative AI
2. **PLC evidence preservation**: Capture-before-restore sequences for critical infrastructure
3. **COO authority gap**: Law firm modernization hampered by governance structures
4. **Pricing professionalization**: Value-based pricing vs. billable hour conflict
5. **Water sector compliance clock**: New York's Jan. 1, 2027 deadline approaching

---

## Sources

- ComplexDiscovery: Water sector guidance analysis
- eDiscovery Today: Five decisions framework
- Legal Tech Monitor: Brad Blickstein interview
- CISA/FBI/EPA alerts: Water sector security

---

*Generated: August 3, 2026 — Monday briefing, water sector evidence preservation, law firm PE thinking, EU AI Act milestone*