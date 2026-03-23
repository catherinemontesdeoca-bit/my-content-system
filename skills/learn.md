# Skill: Learn

Use this skill to teach Claude new brand decisions, exceptions, or patterns.

## How to Use

Tell Claude something new about the project:
> "Learn this: we always use 'workspace' not 'account' in onboarding flows."

Claude will add it to [[../memory|memory.md]] under the right section.

## What Can Be Learned

- **Word choices** — preferred terms, avoided terms, product-specific vocabulary
- **Tone exceptions** — cases where the default rules don't apply
- **Patterns** — recurring copy structures that work well
- **Decisions** — brand or editorial decisions made by the team

## What Won't Be Saved

- Temporary or one-off requests
- Things already documented in [[../CLAUDE.md]]
- Ephemeral context that won't apply in future sessions

## Example

**Input:** "Learn this: in error messages for billing, always include a link to contact support."

**Output:** Claude adds to memory.md:
> **Billing errors** — always include a link to contact support alongside the fix instruction.

---

**Related:** [[../memory]] · [[../CLAUDE.md]]
