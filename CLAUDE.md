# PM Career Ops — AI-powered job search system

Built by [Lachezar Atanasov](https://lachezaratanasov.com) · [LinkedIn](https://www.linkedin.com/in/lachezar-atanasov198/) · [GitHub](https://github.com/ibmlachezar)

---

## What this is

A personal AI job search system that runs inside Claude Code.
Drop in your resume and a job description. Pick a mode. Get a result.

No fluff. No generic advice. Just the output you actually need.

---

## Setup (2 minutes)

1. Install Claude Code: `npm install -g @anthropic-ai/claude-code`
2. Clone this repo: `git clone https://github.com/ibmlachezar/pm-career-ops`
3. Go into the folder: `cd pm-career-ops`
4. Add your resume: paste your resume text into `resumes/my-resume.md`
5. Add a job description: paste it into `job-descriptions/target-role.md`
6. Run Claude Code: `claude`
7. Pick a mode from the list below

---

## The 8 modes

Type any of these commands inside Claude Code:

| Command | What it does |
|---|---|
| `/resume-tailor` | Rewrites your resume for the specific job description |
| `/cover-letter` | Writes a cover letter in your voice for the role |
| `/job-fit` | Scores how well you match the role and what to address |
| `/interview-prep` | Generates the 10 most likely questions + your ideal answers |
| `/linkedin-optimizer` | Rewrites your LinkedIn headline, About, and experience bullets |
| `/outreach-writer` | Writes a cold message to the hiring manager or recruiter |
| `/negotiation-coach` | Prepares you to negotiate an offer for this specific role |
| `/gap-analysis` | Identifies your skill gaps and exactly how to address them |

---

## How to use each mode

### Before running any mode:
- Your resume must be in `resumes/my-resume.md`
- Your target job description must be in `job-descriptions/target-role.md`
- All outputs are saved to `outputs/`

### Example session:
```
claude
> /job-fit
> /resume-tailor
> /interview-prep
```

Run them in that order for the best results. Start with `/job-fit` to understand
where you stand, then tailor your resume, then prep for the interview.

---

## File structure

```
pm-career-ops/
├── resumes/
│   ├── my-resume.md          ← paste your resume here
│   └── example-resume.md     ← example to show the format
├── job-descriptions/
│   ├── target-role.md        ← paste the job description here
│   └── example-jd.md         ← example format
├── outputs/                  ← all generated files land here
├── docs/                     ← guides and tips
├── .claude/
│   └── skills/
│       └── pm-career-ops/    ← the AI skills that power each mode
└── CLAUDE.md                 ← this file (Claude Code reads it automatically)
```

---

## Tips

- The more detail in your resume, the better the output
- Paste the full job description — including requirements and nice-to-haves
- Re-run `/resume-tailor` for each different role — don't reuse the same version
- Use `/gap-analysis` before applying if you're not a strong match — it tells you exactly what to say

---

## Contributing

Found a mode that's missing? Open an issue or PR.
All skill files are plain markdown — easy to read, easy to improve.

## License

MIT
