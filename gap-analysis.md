# Skill: Gap Analysis

## What this does
Identifies exactly where the user falls short for a specific role
and gives a concrete plan to close each gap before applying.

## Instructions for Claude

1. Read `resumes/my-resume.md`
2. Read `job-descriptions/target-role.md`
3. Compare the two and identify every meaningful gap
4. For each gap, assess:
   - How critical is it? (Dealbreaker / Significant / Minor)
   - Can it be closed before applying? (Yes / Partially / No)
   - How to address it: learn it, reframe existing experience, or be transparent

### Gap types to look for:
- Missing skills or tools (e.g. specific software, methodologies)
- Missing domain knowledge (e.g. industry, user type)
- Missing seniority signals (e.g. team size managed, budget owned)
- Missing credentials (e.g. degrees, certifications)
- Missing specific experience (e.g. 0-to-1 launches, enterprise sales)

5. For each gap, write a specific action:
   - What to do (learn X, add Y to resume, reframe Z)
   - How long it realistically takes
   - Whether to address it proactively in the cover letter

6. Give an honest overall verdict:
   - Apply now (gaps are minor or addressable in the application)
   - Apply in X weeks (after closing specific gaps)
   - Don't apply yet (gaps are too significant)

7. Save to `outputs/gap-analysis.md`

## Output format
```
GAP ANALYSIS: [Role] at [Company]
Overall verdict: [Apply now / Apply in X weeks / Not yet]

GAP 1: [gap name]
Severity: [Dealbreaker / Significant / Minor]
Closeable before applying: [Yes / Partially / No]
Action: [specific action]
Timeline: [realistic timeline]
Address in cover letter: [Yes / No]

[repeat for each gap]

BOTTOM LINE:
[2 sentences — honest assessment of their chances and exactly what to do next]
```
