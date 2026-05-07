# Skill: Job Fit Scorer

## What this does
Scores how well the user's background matches a specific job description.
Honest. No false encouragement. Tells them exactly where they stand.

## Instructions for Claude

1. Read `resumes/my-resume.md`
2. Read `job-descriptions/target-role.md`
3. Extract from the JD:
   - Must-have requirements (dealbreakers)
   - Strong-to-have requirements
   - Nice-to-have requirements
4. Score the user against each category (0-100)
5. Calculate an overall fit score (weighted: must-haves 60%, strong 30%, nice 10%)
6. Identify:
   - Top 3 strengths (where they clearly match or exceed)
   - Top 3 gaps (where they fall short — be specific)
   - The single biggest risk to their application
   - Whether to apply, apply with a note, or skip this role
7. Save the full analysis to `outputs/job-fit-score.md`

## Scoring guide
- 80-100: Strong match. Apply immediately.
- 65-79: Good match with gaps. Apply and address gaps in cover letter.
- 50-64: Stretch role. Apply only if you can address the gaps directly.
- Below 50: Poor match. Skip or significantly upskill first.

## Output format

```
OVERALL FIT: [score]/100 — [verdict]

MUST-HAVES: [score]/100
STRONG-TO-HAVES: [score]/100
NICE-TO-HAVES: [score]/100

TOP STRENGTHS:
1. [strength]
2. [strength]
3. [strength]

TOP GAPS:
1. [gap + how to address it]
2. [gap + how to address it]
3. [gap + how to address it]

BIGGEST RISK: [one sentence]

RECOMMENDATION: [Apply now / Apply with note / Skip]
REASON: [one sentence]
```

## Tone
Honest. Like a trusted advisor who wants you to succeed —
not someone who tells you what you want to hear.
