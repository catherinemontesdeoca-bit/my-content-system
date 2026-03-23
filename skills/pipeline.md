# Skill: Content Pipeline

Use this skill to take any content concept from idea to verified, style-guide-ready copy — in four steps.

## How to Use

Give Claude a brief:
> "Run the content pipeline for: [concept, format, audience, goal]"

The more context you give, the better. But even a single concept works — Claude will ask what it needs.

**Useful context to include:**
- What type of content (button, error message, onboarding flow, email, help article, empty state, etc.)
- Who it's for (QuickBooks users, TurboTax customers, accountants, small business owners, etc.)
- What you want the customer to do or feel
- Any constraints (character limits, legal requirements, product context)

---

## Step 1 — Ideation and Research

**Goal:** Explore the concept before writing anything.

Claude will:
1. Restate the brief in plain terms to confirm understanding
2. Identify the customer's likely emotional state at this moment
3. Identify the tone spectrum position — is this more emotional or more functional?
4. Generate 3 content angles to explore:
   - **Benefits-led** — focuses on what the customer gains
   - **Action-led** — focuses on what the customer does
   - **Empathy-led** — acknowledges where the customer is emotionally
5. Recommend which angle fits best, and why

Output: a short ideation summary with the recommended angle highlighted.

---

## Step 2 — Draft

**Goal:** Write clean, simple copy based on the chosen angle and user requirements.

Claude will:
1. Write the copy using the recommended angle from Step 1 (or the angle you choose)
2. Apply the correct rules for the copy type:

| Type | Key rules |
|---|---|
| Button / CTA | Verb + outcome, sentence case, no period |
| Error message | Acknowledge → explain → fix, no blame |
| Empty state | Explain purpose + clear next action |
| Tooltip / helper text | 1 sentence, front-load key info, no "This is" opener |
| Header / headline | Tight + specific, sentence case, no period |
| Body copy | Active voice, second person, 5th–8th grade reading level |
| Email subject | Punchy, benefit-forward |
| Celebration | Only for genuine customer milestones |

3. Produce 2 draft variations (A and B) so you have options to compare

Output: Draft A and Draft B, with a note on what's different between them.

---

## Step 3 — Verify

**Goal:** Check both drafts against the Intuit style guide rules.

Claude runs the 7-point checklist on each draft:

1. **Active voice?**
2. **CTA has verb + outcome?**
3. **Sentence case?**
4. **Reading level 5th–8th grade?** (short words, simple tenses)
5. **Superlatives and hype removed?** (best, top, world-class, amazing, great, ultimate)
6. **Respecting emotions, not directing them?** (no "You're going to love this" or "Great news!")
7. **Friendly colleague test?**

And checks for avoided words:

| Flag | Replace with |
|---|---|
| Please | (just say what to do) |
| Sorry | (acknowledge and fix) |
| Invalid | Not valid / incorrect |
| Failed | Couldn't / wasn't able to |
| Abort | Cancel |
| Kill | Stop / end |
| Simple / Simply | (remove) |
| Since (causal) | Because |
| Above / Below | Name the element |

Output: a checklist result for Draft A and Draft B, with each issue flagged and a suggested fix.

---

## Step 4 — Gatekeeper Score

**Goal:** Give each draft a score so you know how close it is to style guide compliance.

**Scoring rubric (100 points total):**

| Category | Points | What's being measured |
|---|---|---|
| Active voice | 15 | No passive constructions |
| CTA format | 15 | Verb + outcome (if applicable) |
| Sentence case | 10 | Correct capitalization throughout |
| Reading level | 15 | 5th–8th grade words and sentences |
| No superlatives or hype | 15 | Clean of exaggeration |
| Emotional respect | 15 | Doesn't tell customers how to feel |
| Avoided words | 10 | None of the flagged words present |
| Brand character | 5 | Warm, confident, genuine |

**Score bands:**

| Score | Verdict |
|---|---|
| 90–100 | ✅ Ready to ship |
| 75–89 | 🔁 Minor revisions needed |
| 50–74 | ⚠️ Significant revisions needed |
| Below 50 | ❌ Rewrite recommended |

Output: a score for Draft A and Draft B, a breakdown by category, and a recommended draft to move forward with.

---

## Full Pipeline Output Example

**Brief:** "Onboarding empty state for QuickBooks — no invoices yet. New user, first login."

---

### Step 1 — Ideation
- Customer state: excited but uncertain, just getting started
- Tone position: warm, slightly emotional
- Angle A (Benefits-led): "Here's what invoicing can do for your cash flow"
- Angle B (Action-led): "Send your first invoice in under 2 minutes"
- Angle C (Empathy-led): "Every business starts somewhere. Yours starts here."
- **Recommended:** Angle B — action-led is clearest for an empty state; gets the customer moving

---

### Step 2 — Draft

**Draft A**
> No invoices yet.
> Send your first invoice and start getting paid faster.
> **Create invoice**

**Draft B**
> Your invoices will show up here.
> Ready to get paid? It only takes a minute.
> **Send your first invoice**

---

### Step 3 — Verify

| Check | Draft A | Draft B |
|---|---|---|
| Active voice | ✅ | ✅ |
| CTA verb + outcome | ✅ Create invoice | ✅ Send your first invoice |
| Sentence case | ✅ | ✅ |
| Reading level | ✅ | ✅ |
| No superlatives | ✅ | ✅ |
| Emotional respect | ✅ | ✅ |
| Avoided words | ✅ | ✅ |

No issues found in either draft.

---

### Step 4 — Gatekeeper Score

| Category | Draft A | Draft B |
|---|---|---|
| Active voice | 15/15 | 15/15 |
| CTA format | 15/15 | 15/15 |
| Sentence case | 10/10 | 10/10 |
| Reading level | 15/15 | 15/15 |
| No superlatives | 15/15 | 15/15 |
| Emotional respect | 15/15 | 15/15 |
| Avoided words | 10/10 | 10/10 |
| Brand character | 5/5 | 4/5 |
| **Total** | **100/100 ✅** | **99/100 ✅** |

**Recommended:** Draft A — slightly more direct; "Create invoice" is cleaner than "Send your first invoice" for a button.

---

**Related:** [[tone-checker]] · [[learn]] · [[../CLAUDE.md]]
