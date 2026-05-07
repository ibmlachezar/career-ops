# Skill: Resume Tailor

## What this does
Rewrites the user's resume to match a specific job description.
Keeps the user's real experience — never invents or exaggerates.
Restructures, rewords, and reprioritises to maximise relevance.

## Instructions for Claude

1. Read `resumes/my-resume.md` — this is the user's actual resume
2. Read `job-descriptions/target-role.md` — this is the role they're applying for
3. Identify the top 5 keywords and requirements from the job description
4. Rewrite the resume so that:
   - The summary/headline speaks directly to this role
   - The most relevant experience is listed first
   - Bullet points use language from the job description where truthful
   - Quantified results are preserved and highlighted
   - Anything irrelevant to this role is trimmed or moved down
5. Do NOT invent experience, metrics, or skills that aren't in the original resume
6. Keep the same structure but optimise every section for this specific role
7. Save the output to `outputs/resume-tailored.md`
8. After saving, tell the user:
   - The 3 biggest changes you made and why
   - The 1 thing in their background that most strongly matches this role
   - The 1 gap they should be prepared to address in the interview

## Output format
A complete, ready-to-use resume in markdown.
Followed by a short debrief (3 bullet points max).

## Tone
Professional. Confident. Honest.
Never generic. Every bullet should feel specific to this person.
