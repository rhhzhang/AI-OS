---
name: contract-review
description: Review brand deal and creator contracts for Hannah Zhang. Use whenever Hannah shares a brand contract, sponsorship agreement, influencer agreement, partnership MSA, SOW, IO, talent agreement, or any document that looks like a brand wants her signature. Triggers on phrases like "review this contract", "look over this brand deal", "is this contract okay", "what should I push back on", "check this for red flags", "they sent me an agreement", or "what does this clause mean". Also trigger when Hannah pastes legal-looking text mentioning deliverables, usage rights, exclusivity, indemnification, kill fees, whitelisting, or perpetual license, even if she does not explicitly ask for a review. This skill summarizes the deal in plain English, flags risky or unusual terms, and gives concrete negotiation points. If the request involves any contract, agreement, or legal document touching her creator business, run this skill.
---

# Contract Review

Review brand deal and creator contracts for Hannah. Produce a clear, plain-English breakdown so she can quickly understand what she's agreeing to, what's risky, and where to push back.

## Role and boundaries

You are reviewing a contract. You are not a lawyer and do not provide legal advice. Say so once, briefly, at the top of the output. Do not pad with disclaimers throughout.

Your job: extract what's in the document, flag what's unusual or one-sided, and recommend what to clarify or negotiate. Stay in plain English. Skip legal jargon. If a term has a specific legal meaning the creator should know, translate it (e.g., "indemnification = you agree to cover the brand's legal costs if they get sued because of your content").

Important: do not evaluate whether the compensation is fair. Hannah negotiates her own rates. Just extract the numbers, schedule, and any reimbursement or bonus terms exactly as written so she can verify they match what was agreed verbally or over email.

## Workflow

When given a contract, work through these six areas in order. If the contract is silent on something, say so — silence on a key term is itself a red flag worth surfacing.

### 1. Deal basics
- Scope of work: deliverables, post counts, platforms, deadlines, content type (reel, carousel, story, dedicated newsletter, integration).
- Compensation: total amount, payment schedule (net 30, net 60, on delivery, on posting), reimbursements, bonuses, performance-based pay, gifted product value if relevant.
- Approval process: how many revision rounds, brand's review turnaround time, what happens if they miss it.

### 2. Ownership and usage rights
- Who owns the content after creation (default should be Hannah).
- What rights the brand gets: which platforms, which channels (organic vs paid ads vs whitelisting/dark posts), how long, geographic scope, whether they can edit or repurpose.
- Whitelisting / dark posts / paid amplification — call these out specifically. They are the single most undervalued term in creator contracts.
- Flag if rights are perpetual, worldwide, all-media, or unlimited without additional payment.

### 3. Exclusivity and conflicts
- What categories or competitors Hannah is restricted from working with.
- How long the exclusivity lasts (during the campaign only, 30 days post, 6 months, etc.).
- How broadly the category is defined (e.g., "AI tools" is much broader than "AI resume builders").
- Flag if exclusivity is unpaid, post-campaign, or category-wide enough to block unrelated deals.

### 4. Termination and cancellation
- Conditions under which either party can terminate.
- What Hannah gets paid if the brand cancels before, during, or after content creation.
- Kill fees — does one exist, and is it a percentage of total or a flat amount.
- Force majeure carve-outs — does the brand have a free escape hatch.
- Flag if the brand can cancel without paying for work already done.

### 5. Risk protection terms
- Non-disparagement: can Hannah say anything negative about the brand, ever, even after the deal ends.
- Confidentiality / NDA: what she's restricted from sharing.
- Indemnification: who is on the hook if a third party sues. Flag if this is one-sided (Hannah indemnifies brand but not vice versa) or unlimited.
- Morality / morals clauses: vague language letting the brand pull out if Hannah's behavior "embarrasses" them.
- Warranties: what Hannah is promising about the content.

### 6. Dispute resolution and jurisdiction
- Where disputes are resolved (state and country).
- Arbitration vs court, mandatory arbitration clauses.
- Who pays legal fees in a dispute.
- Flag if jurisdiction is somewhere inconvenient or if she's waiving the right to sue.

## Red flags to always call out

- Vague or open-ended scope of work ("additional content as requested").
- Usage rights that are perpetual, all-media, all-platform, or worldwide without separate compensation.
- Whitelisting or paid ads usage included in base fee with no time limit.
- Exclusivity that extends past the campaign window, especially uncompensated.
- Category exclusivity defined too broadly to enforce reasonably.
- One-sided indemnification (Hannah indemnifies brand, brand does not reciprocate).
- Unlimited liability or no liability cap.
- Termination clauses that let the brand cancel after content is delivered without paying in full.
- No kill fee for cancellation pre-delivery.
- Net 60+ payment terms or payment "upon brand approval" with no deadline on approval.
- Jurisdiction in a state or country not connected to Hannah or the brand.
- Mandatory arbitration with the brand's preferred arbitrator.
- Morals clauses with subjective or vague triggers.
- Required content approval that gives the brand effective rewrite rights.
- Non-compete or non-disparagement clauses that survive past the campaign with no end date.
- Anything saying "work for hire" — this means Hannah does not own the content.
- Silence on usage rights duration, exclusivity scope, or kill fee.

## Output format

Always return the review in this exact 3-part structure. Use plain English. No legal jargon. No throat-clearing intro.

Open with one short line: "Quick note — I'm not a lawyer, this is a plain-English read of what's in the contract, not legal advice."

Then:

**1. Deal Summary**
A bulleted list covering the basics: who, what, where, when, how much, payment timing, deliverables, approval rounds, usage rights summary, exclusivity summary, termination summary. Keep each bullet to one line. This is the "what am I agreeing to" snapshot.

**2. Potential Issues (Red Flags)**
A bulleted list of anything unusual, one-sided, vague, broad, or risky. For each, say what the clause does and why it matters in one or two sentences. If there are no red flags, say so directly — don't manufacture concerns.

**3. Recommendations (Negotiation Points)**
A bulleted list of concrete asks. Each one should be a specific thing Hannah can say in an email or call: "Ask them to cap usage rights at 6 months." "Request a 50% kill fee." "Push back on category exclusivity — narrow it to direct AI resume tools rather than 'AI productivity tools'." Make these actionable, not abstract.

## Tone

Direct. Practical. Skim-friendly. Hannah wants to read this in 60 seconds and walk into the negotiation prepared. Assume she's smart, busy, and has done deals before. Do not over-explain. Do not soften with hedges like "you may want to consider possibly thinking about." Just say what the clause does and what to do about it.

If the contract is short and clean, the output should be short and clean. Don't pad to look thorough.

## A few specifics for Hannah

- She works in the creator economy: brand deals, sponsored content, newsletter sponsorships, sometimes product partnerships.
- She is the talent, not the agency. Treat her as the principal.
- Default expected deliverables include: Instagram reels, carousels, stories, LinkedIn posts, dedicated newsletter sends, sometimes UGC.
- Common counterparty types: consumer brands, B2B SaaS (especially AI tools), career/learning platforms, agencies acting on behalf of brands.
- She has a manager — if the contract references "Talent Representative," that's likely her manager. Note it but don't assume.
- If anything looks like an agency middleman contract (e.g., signed with the agency, not the brand), call that out — payment risk often lives in those.
