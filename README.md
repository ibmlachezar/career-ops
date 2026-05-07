# ♟ PM Career Ops

**AI-powered job search system for people who want an edge.**

8 modes. Drop in your resume and a job description. Get results in seconds.
Built for any role — tech, product, business, or anything else.

---

## What it does

Most job search advice is generic. This isn't.

PM Career Ops reads YOUR resume and a SPECIFIC job description, then runs one of 8 targeted modes to give you exactly what you need — tailored to that role, in your voice.

| Mode | Command | What you get |
|------|---------|-------------|
| Job Fit Scorer | `/job-fit` | Honest score of how well you match the role |
| Gap Analysis | `/gap-analysis` | Exactly what's missing and how to close it |
| Resume Tailor | `/resume-tailor` | Your resume rewritten for this specific role |
| Cover Letter | `/cover-letter` | A cover letter that doesn't sound like a template |
| LinkedIn Optimizer | `/linkedin-optimizer` | Headline, About, and bullets rewritten for the role |
| Outreach Writer | `/outreach-writer` | Cold message to the hiring manager — short, specific, gets replies |
| Interview Prep | `/interview-prep` | 10 likely questions + your ideal answers using your background |
| Negotiation Coach | `/negotiation-coach` | Exact words to use when negotiating your offer |

---

## Setup

**Requirements:** [Claude Code](https://claude.ai/code) (free to install)

```bash
# 1. Install Claude Code
npm install -g @anthropic-ai/claude-code

# 2. Clone this repo
git clone https://github.com/ibmlachezar/pm-career-ops
cd pm-career-ops

# 3. Add your resume
# Open resumes/my-resume.md and paste your resume
# (follow the format in resumes/example-resume.md)

# 4. Add the job description
# Open job-descriptions/target-role.md and paste the full JD

# 5. Start Claude Code
claude

# 6. Pick a mode
> /job-fit
```

---

## Recommended order

Run these in sequence for the best results:

```
/job-fit          → understand where you stand
/gap-analysis     → know what to address  
/resume-tailor    → rewrite your resume for this role
/cover-letter     → write the letter
/linkedin-optimizer → align your LinkedIn
/outreach-writer  → reach out before applying
/interview-prep   → prepare for the call
/negotiation-coach → handle the offer
```

---

## File structure

```
pm-career-ops/
├── resumes/
│   ├── my-resume.md          ← your resume goes here
│   └── example-resume.md     ← format guide
├── job-descriptions/
│   ├── target-role.md        ← job description goes here
│   └── example-jd.md         ← format guide
├── outputs/                  ← all generated files (gitignored)
├── docs/
│   └── tips.md               ← how to get the best results
├── .claude/
│   └── skills/
│       └── pm-career-ops/    ← the 8 skill files
└── CLAUDE.md                 ← Claude Code reads this automatically
```

---

## Privacy

Your resume and job descriptions are **gitignored by default** — they never get committed to git or shared anywhere. Everything runs locally through Claude Code on your machine.

---

## Tips

- The more specific your resume (real numbers, real outcomes), the better the output
- Paste the full job description — including requirements and nice-to-haves
- Run `/resume-tailor` fresh for each different role — never reuse the same version
- See `docs/tips.md` for the full guide

---

## Built by

**Lachezar Atanasov** — Head of AI Product, AI startup founder, advisor to multiple AI companies.

→ [lachezaratanasov.com](https://lachezaratanasov.com)
→ [LinkedIn](https://www.linkedin.com/in/lachezar-atanasov198/)
→ [ai-product-toolkit](https://github.com/ibmlachezar/ai-product-toolkit) ← my other open source tool

---

## Contributing

Found a mode that's missing? Have an improvement to one of the skill files?
Open an issue or submit a PR. All skill files are plain markdown — easy to read and improve.

## License

MIT — use it, fork it, build on it.
