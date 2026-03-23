# Skill: Tone Checker

Use this skill to review copy against Intuit's content design guidelines.

## How to Use

Paste any copy and tell Claude what type it is:
> "Check this button copy against our tone guidelines: [copy]"
> "Tone check this error message: [copy]"

**Copy types:** button/CTA, error message, empty state, tooltip/helper text, header/headline, body copy, email subject, celebration

If you don't specify the type, Claude will ask before reviewing.

---

## Step 1 — Identify copy type

Different rules apply depending on where the copy appears.

| Type | Tone | Key rules |
|---|---|---|
| Button / CTA | Functional | Verb + outcome, sentence case, no period |
| Error message | Functional-warm | Acknowledge → explain → fix, no blame, no avoided words |
| Empty state | Warm | Explain purpose + give a clear next action |
| Tooltip / helper text | Functional | 1 sentence max, front-load key info, never start with "This" or "This is" |
| Header / headline | Emotional | Tight + specific, sentence case, no period |
| Body copy | Emotional-functional | Active voice, 5th–8th grade reading level, second person |
| Email subject | Emotional | Punchy, benefit-forward |
| Celebration | Emotional | Only for genuine customer milestones — never routine tasks |

---

## Step 2 — Run the 7-point checklist

1. **Active voice?** "Save your settings" not "Your settings have been saved"
2. **CTA has verb + outcome?** "Start free trial" not "Click here" or "Submit"
3. **Sentence case throughout?** "Add team member" not "Add Team Member"
4. **Reading level 5th–8th grade?** Short words (3–5 letters beat 8–9), simple tenses (save vs. be saving), familiar language
5. **Superlatives and hype removed?** Flag: best, top, world-class, amazing, ultimate, premier, most-trusted, great → use facts or "good"
6. **Respecting emotions, not directing them?** Don't say "You're going to love this" or "Great news!" — let customers feel what they feel
7. **Friendly colleague test?** Would a warm, knowledgeable colleague say this out loud?

---

## Step 3 — Check avoided words

Flag any of these and suggest a replacement:

| Flag | Use instead |
|---|---|
| Please | (just say what to do) |
| Sorry | (acknowledge and fix) |
| Invalid | Not valid / incorrect |
| Failed | Couldn't / wasn't able to |
| Abort | Cancel |
| Kill | Stop / end |
| Simple / Simply | (remove — simplicity is subjective) |
| Since (causal) | Because |
| Above / Below (directional) | Name the exact element or step |
| Don't worry (serious context) | (remove or reframe) |

---

## Step 4 — Brand character gut check

Does the copy feel:
- **Warm** but not sappy or over-the-top?
- **Confident** but not arrogant or full of itself?
- **Genuine** — transparent and clear, not corporate or sugarcoated?

---

## Output Format

For each issue found:

- **Type:** what kind of copy this is
- **Issue:** which rule is broken
- **Original:** the copy as written
- **Suggested fix:** the revised version
- **Why:** which guideline it violates

End every review with:
- **Verdict:** Pass ✅ or Needs work 🔁
- **Summary:** one sentence on the biggest thing to fix (or confirm if it's clean)

---

## Examples

### Example 1 — Button copy

**Input:** "Click here to get started with our world-class invoicing tool!"

- **Type:** Button / CTA
- **Issue:** No verb + outcome; superlative; exclamation mark; title case
- **Original:** "Click here to get started with our world-class invoicing tool!"
- **Suggested fix:** "Create your first invoice"
- **Why:** CTAs need verb + outcome; "world-class" is hype; exclamation marks inflate routine actions; sentence case required

**Verdict:** Needs work 🔁
**Summary:** Rewrite as a verb + outcome in sentence case and drop the superlative.

---

### Example 2 — Error message

**Input:** "Sorry, your payment failed. Invalid card number. Please try again."

- **Type:** Error message
- **Issue 1:** Uses "Sorry" (avoided word)
- **Issue 2:** Uses "failed" (avoided word) — use "couldn't"
- **Issue 3:** Uses "Invalid" (avoided word) — use "incorrect"
- **Issue 4:** Uses "Please" (avoided word)
- **Issue 5:** Blames the user implicitly; no explanation of next step
- **Original:** "Sorry, your payment failed. Invalid card number. Please try again."
- **Suggested fix:** "We couldn't process your payment. Check that your card number is correct and try again."
- **Why:** Error messages should acknowledge → explain → fix, never blame, and avoid the word list above

**Verdict:** Needs work 🔁
**Summary:** Remove all avoided words and rewrite to acknowledge, explain, and guide — without blame.

---

**Related:** [[../Brand Voice/Writing Rules]] · [[../Brand Voice/Words to Avoid]] · [[../CLAUDE.md]]
