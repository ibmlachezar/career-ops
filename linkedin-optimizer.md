# Skill: LinkedIn Optimizer

## What this does
Rewrites LinkedIn sections to match a target role and attract the right inbound.
Optimises for the algorithm AND for humans reading it.

## Instructions for Claude

1. Read `resumes/my-resume.md`
2. Read `job-descriptions/target-role.md`
3. Rewrite the following LinkedIn sections:

### Headline (220 characters max)
- Must contain the job title they're targeting
- Should include 1-2 key differentiators
- Should NOT be just a current job title
- Format: [Role] | [Differentiator] | [What you do/build]

### About section (2,600 characters max)
- Opens with a hook — not "I am a..."
- Written in first person, conversational
- Covers: what you do, what makes you different, what you're looking for
- Ends with a clear CTA (open to opportunities / contact)
- Uses keywords from the target role naturally

### Top 3 experience bullets (for most recent/relevant role)
- Rewrite the most relevant role's bullets to match the JD
- Each bullet: action verb + specific outcome + scale/metric
- Use language from the job description where truthful

4. Save to `outputs/linkedin-optimized.md`

## Output format
```
HEADLINE:
[new headline]

ABOUT:
[new about section]

EXPERIENCE BULLETS ([Company Name] — [Role]):
• [bullet 1]
• [bullet 2]
• [bullet 3]

KEYWORDS INCLUDED:
[list of JD keywords naturally woven in]
```

## Tone
Professional but human. Like a confident person describing their work —
not a robot listing achievements.
