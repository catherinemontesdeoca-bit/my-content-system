# Skill: Tone Checker

Use this skill to review copy against Aircall's brand voice guidelines.

## How to Use

Paste any UI copy, microcopy, or draft content and ask:
> "Check this against our tone guidelines."

## What Gets Checked

1. **Active voice** — "Save your settings" not "Your settings have been saved"
2. **CTA format** — verb + outcome ("Start free trial", not "Click here")
3. **Sentence case** — everywhere, including buttons and headings
4. **Avoided words** — no "Please", "Sorry", "Failed", "Invalid", "Abort", "Kill"
5. **Error message structure** — acknowledge → explain → fix, never blame the user
6. **Warmth** — would a friendly colleague say this out loud?

## Output Format

For each flagged item:
- **Issue:** what's wrong
- **Original:** the copy as written
- **Suggested fix:** the revised version
- **Why:** which rule it breaks

## Example

**Input:** "Sorry, your password is invalid. Please try again."

**Output:**
- **Issue:** Uses "Sorry" and "Invalid" (avoided words); passive blame on user
- **Original:** "Sorry, your password is invalid. Please try again."
- **Suggested fix:** "That password didn't work. Double-check it and try again."
- **Why:** Removes avoided words, stays warm, gives a clear next action

---

**Related:** [[../Brand Voice/Writing Rules]] · [[../Brand Voice/Words to Avoid]]
