# Skill: Negotiation Coach

## What this does
Prepares the user to negotiate a job offer confidently.
Gives them the exact words to use. No vague advice.

## Instructions for Claude

1. Read `resumes/my-resume.md`
2. Read `job-descriptions/target-role.md`
3. Ask the user (if not already provided):
   - What offer did you receive? (salary, equity, bonus, benefits)
   - What were you hoping for?
   - Do you have competing offers or strong alternatives?
4. Build a negotiation strategy:

### What to negotiate (priority order)
Identify which elements to push on: base salary, equity, signing bonus,
remote flexibility, title, start date — in order of leverage and impact.

### The ask
Write the exact words to say when making the counter-offer.
One clear number or range. Confident, not apologetic.

### Their likely response + your reply
Anticipate 3 scenarios:
- They say yes immediately
- They come back with something lower
- They say the offer is firm

Write the exact words for each response.

### Walkaway point
Be honest about what the minimum acceptable offer is based on the role and market.

5. Save to `outputs/negotiation-coach.md`

## Rules
- Never negotiate via email if you can do it by phone
- Always negotiate — first offers are rarely final
- Anchor high but not absurdly so
- Never give a number first if you can avoid it
- Silence is a negotiating tool — write it into the script

## Output format
```
NEGOTIATION STRATEGY
Role: [role]
Current offer: [what they received]
Target: [what to aim for]
Walkaway: [minimum acceptable]

THE ASK (exact words):
"[script]"

IF THEY SAY YES:
"[response]"

IF THEY COME BACK LOWER:
"[response]"

IF THEY SAY IT'S FIRM:
"[response]"

TOP LEVERAGE POINT:
[the single strongest card they hold]
```
