```markdown
# The Leak Report — 4-Step Prompt Chain

## Overview

This document contains the complete prompt chain for generating a **"One Leak. One Fix."** audit for any Mom & Pop business URL. The chain is designed to be copy-pasted into any AI (Claude, ChatGPT, Gemini) and run sequentially.

**The Promise:** In under 5 minutes, you can generate a 1-page PDF that identifies the single biggest conversion leak, provides a 2-minute fix, and quantifies the monthly dollar loss — all without spending a dime.

**The Fused Lens:** Each prompt is infused with the copywriter persona lens — conversational authority, relentless empathy, PVAs, and the Granny Rule.

---

## Prompt P1 — Raw Data Extraction

**Purpose:** Extract observable, factual data from the target URL. Do not interpret. Do not judge. Just extract.

**Copy and paste this prompt, replacing [PASTE TARGET URL HERE] with the actual URL:**

---

```

You are a conversion analyst. I will give you a URL. You will visit it (simulate) and extract ONLY observable, factual data. Do not interpret yet. Do not judge. Just extract.

URL: [PASTE TARGET URL HERE]

Extract the following in bullet points:

1. Page load speed observations (from memory): Is it heavy with images? Is there a delay before the main content appears? Is the mobile version truncated?
2. Above‑the‑fold content (first screen visible without scrolling):
   · What is the headline? (exact words)
   · Is there a phone number? If yes, where is it located (top right, center, bottom?) and is it clickable?
   · Is there a call‑to‑action button? (exact text)
   · Is there an image/video? What does it show?
3. Below‑the‑fold content (after scrolling):
   · Services or products listed (how many?)
   · Testimonials or reviews (visible or hidden behind a tab?)
   · About section (tone: personal vs corporate?)
   · Any forms? Where are they placed?
4. Navigation:
   · How many menu items?
   · Is there a "Contact" page link? Is it prominent?
5. Footer:
   · Phone number repeated?
   · Social media links? Are they active?

Output as a clean bulleted list. No commentary. Just facts.

```

---

## Prompt P2 — Identify the Single Biggest Leak

**Purpose:** Analyze the raw data and identify the ONE element that is leaking the most calls/sales. Quantify the monthly dollar loss conservatively.

**Copy and paste this prompt, including the output from P1:**

---

```

You are a conversion surgeon. Review the raw data below. Your task: identify the ONE single element that is leaking the most calls/sales for this Mom & Pop business.

Criteria for the "biggest leak":

· It is visible within the first 3 seconds of landing.
· It creates confusion, hesitation, or friction.
· Fixing it requires minimal effort (text change, button move, color swap).
· Fixing it will produce a measurable lift in phone calls or form submissions within 7 days.

From the data, select exactly ONE leak. Then answer these three questions:

1. WHAT is the leak? (Describe it in plain language a business owner would understand. Use PVAs — Powerful Visual Adjectives.)
2. WHY does it leak? (Psychological reason: e.g., "visitors feel unsafe," "they don't know what to do next," "they think you're too expensive.")
3. QUANTIFY the leak: Estimate how many visitors abandon per week due to this. Use a conservative calculation: e.g., "If you get 100 visitors/week, and 40% look for your phone number but can't find it, that's 40 missed opportunities. At a 10% close rate, that's 4 lost calls/week. At $100 average ticket, that's 1,600/month."

Output in this exact format:

LEAK: [One sentence, with a PVA]
WHY: [One sentence, psychological]
LOSS: [Calculate in dollars per month, using their estimated traffic from the page]

```

---

## Prompt P3 — Generate the Specific Fix

**Purpose:** Generate a step-by-step fix that the business owner can implement in under 5 minutes with zero tools or design skills.

**Copy and paste this prompt, including the output from P2:**

---

```

You are a fixer. Based on the leak identified, generate a specific, actionable fix.

Rules for the fix:

· Must be executable by the business owner in under 5 minutes.
· Must require zero new tools, zero coding, zero design skills.
· Must provide exact wording if text needs changing.
· Must provide exact placement if positioning changes.
· Must include a before/after visual description (so I can mock it up in Canva).

Output in this exact format:

FIX: [One sentence summary, with a PVA]
EXACT CHANGE: [Bulleted list of step‑by‑step actions]
BEFORE (current state): [Describe current text/placement]
AFTER (changed state): [Describe new text/placement]
WHY THIS WORKS: [One sentence psychological justification]

```

---

## Prompt P4 — Format the Final PDF Content

**Purpose:** Generate the final 1-page PDF text, ready to copy-paste into Canva or Word.

**Copy and paste this prompt, including outputs from P2 and P3:**

---

```

You are a copywriter for a local business audit. Using the Leak and Fix data provided, generate the final copy for a 1‑page PDF titled: "One Leak. One Fix."

This PDF will be sent to the business owner immediately after the voice memo. Write in the voice of a local market analyst — conversational, empathetic, urgent without desperation. Use PVAs. Pass the Granny Rule.

Structure:

HEADER: "One Leak. One Fix. [Business Name]"

SECTION 1: The Leak
Copy the LEAK and LOSS from P2, formatted as a short paragraph. Drop them into the problem. Make them feel the cost.

SECTION 2: The Fix
Copy the FIX and EXACT CHANGE from P3, formatted as numbered steps. Make it ridiculously easy to implement.

SECTION 3: The Prediction
Write 2‑3 sentences predicting the result: "If you make this change today, expect X more calls this week. That's $Y in your pocket." Be conservative. Be honest.

SECTION 4: The Next Step
Copy this exactly:
"If you want me to find the other 4 leaks I spotted, reply to this email with 'MORE' and I'll send a full breakdown—no charge, no obligation, just data."

FOOTER:
No branding, no logo, no "about me." Just a plain text line: "— A local market analyst"

Generate the full PDF text now. Make it warm, direct, and human. No corporate jargon. Write as if you're talking to a neighbor over a fence.

```

---

## The 5-Point Human Filter Checklist

**Purpose:** Before sending any PDF, apply these 5 filters to ensure the copy passes the cultural accuracy test. This is your 10% human edge.

| # | Question | If "No" — Fix It |
| :--- | :--- | :--- |
| 1 | Does this sound like it was written by someone who *knows* struggle? | Add a line like: "I know how hard it is to get people to pick up the phone. I've been there." |
| 2 | Does it acknowledge the client's *existing* creativity (not just their gaps)? | Add: "Your site already has the bones. We just need to move one thing." |
| 3 | Is the call‑to‑action *urgent* without being *desperate*? | Change "Reply now" to "Reply when you're ready—I'll be here." |
| 4 | Does it use the client's *specific* vocabulary (not generic marketing terms)? | Replace "conversion" with "calls." Replace "traffic" with "people visiting your site." |
| 5 | Would I say this to my own mother? | If it sounds like a sales pitch, rewrite it to sound like a *heads‑up*. |

---

## The Final Output — Example (For a Plumber)

*This is what P4 produces after running through the chain:*

---

**One Leak. One Fix. Johnson's Plumbing.**

**The Leak:**
Your phone number is buried at the bottom of your homepage, hidden below three paragraphs about your 20 years of experience. Most folks don't scroll that far—they're busy, they're on their phone, they need an answer *now*. They land, they look for a number, they don't see it, they leave. Based on your site traffic, that's about 40 missed calls a month. At your average job ticket of $400, that's roughly $1,600 in lost work—every month.

**The Fix:**
1. Move your phone number to the top‑right corner of your header—right next to your logo.
2. Make it bold, blue, and clickable on mobile.
3. Change the text from "(555) 123‑4567" to "CALL FOR A FREE QUOTE — (555) 123‑4567."

**The Prediction:**
If you make this change today, expect 2‑3 extra calls this week. Not 20. Just 2‑3. At $400 per job, that's $800‑$1,200 in your pocket—from a 2‑minute fix. That pays for itself before the weekend.

**The Next Step:**
If you want me to find the other 4 leaks I spotted, reply to this email with 'MORE' and I'll send a full breakdown—no charge, no obligation, just data.

— A local market analyst

---

## Execution Checklist

| Step | Action | Time |
| :--- | :--- | :--- |
| 1 | Copy P1 → Paste into AI with URL | 1 min |
| 2 | Copy P2 → Paste AI output | 1 min |
| 3 | Copy P3 → Paste AI output | 1 min |
| 4 | Copy P4 → Paste AI output | 1 min |
| 5 | Apply 5‑point filter (manual edit) | 60 sec |
| 6 | Copy final text into Canva → Export as PDF | 2 min |
| 7 | Send PDF via email/text | 1 min |
| **Total per lead** | **~8 minutes** | |

---

## Quick Reference — Prompt Chain Summary

| Prompt | Purpose | Output |
| :--- | :--- | :--- |
| P1 | Raw Data Extraction | Bulleted list of page facts |
| P2 | Leak Identification | LEAK, WHY, LOSS (monthly $) |
| P3 | The Fix | FIX, EXACT CHANGE, BEFORE, AFTER, WHY |
| P4 | Final PDF Copy | Ready‑to‑paste 1‑page PDF content |
| Filter | Human Polish | Culturally accurate, empathetic copy |

---

**End of 05_PROMPT_CHAIN.md**
```

---

