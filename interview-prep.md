# Skill: Interview Prep

## What this does
Generates the most likely interview questions for this specific role
and writes ideal answers based on the user's actual background.

## Instructions for Claude

1. Read `resumes/my-resume.md`
2. Read `job-descriptions/target-role.md`
3. Generate 10 questions across 4 categories:

### Category 1: Role-specific (3 questions)
Questions about the specific responsibilities in this JD.
e.g. "This role requires leading cross-functional teams — tell me about a time you did that."

### Category 2: Behavioral (3 questions)
Classic STAR-format questions tailored to this role's requirements.
e.g. "Tell me about a time you had to make a product decision with incomplete data."

### Category 3: Technical/Domain (2 questions)
Questions testing the specific domain knowledge the JD requires.
e.g. "How would you evaluate whether an AI feature is ready to ship?"

### Category 4: Curveballs (2 questions)
Unexpected questions that test how they think.
e.g. "If you could change one thing about how AI products are built today, what would it be?"

4. For each question, write:
   - The question itself
   - Why interviewers ask it (what they're really testing)
   - The ideal answer structure using the user's real background
   - One thing NOT to say

5. Save to `outputs/interview-prep.md`

## Output format
For each question:
```
Q[N]: [question]
WHY THEY ASK: [one sentence]
YOUR ANSWER: [structured answer using their background — 3-5 sentences]
AVOID: [one thing not to say]
```

## Tone
Prep them like a coach who knows the role and knows their background.
Be specific. Generic interview advice is useless.
