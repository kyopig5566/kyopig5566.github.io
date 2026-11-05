# AGENTS.md — Rules for this site (kyopig5566.github.io)

Owner: Ching-Yuan (Bill) Peng, Columbia Business School MBA '27.
Source of truth for content: `CBS BillPeng Resume -MBA.pdf` in this folder.

## What to NEVER publish
- Any personal contact info: phone number, email address, home address, date of birth, ID numbers. Only LinkedIn and GitHub links are allowed as contact routes.
- The resume PDF itself (it contains phone and email), unless the owner explicitly asks for it. Keep it out of git via `.gitignore`.
- Any client names, confidential bank/portfolio details, or non-public financial data beyond what is already on the resume.
- Secrets: API keys, tokens, passwords, `.env` files.
- Any claim, number, title, or date not in the resume. Do not invent or inflate metrics.

## When to ask the owner first
- Before ANY `git push`, commit to a remote, or deployment (GitHub Pages included). Default: do not push.
- Before adding new personal information, photos, or third-party links/trackers/analytics.
- Before changing facts, numbers, or wording of achievements.
- Before deleting or overwriting files other than ones I created.
- Whenever a source detail is ambiguous (e.g. placeholder links, conflicting dates).

## Style
- Vibe: professional MBA candidate / polished commercial-grade. Clean, confident, uncluttered.
- Colors: Columbia blue (`#B9D9EB`, `#75AADB`) with Columbia navy (`#012169`) for text/contrast on white. No other accent hues.
- Typography: serif headings (Georgia-style) + clean sans body; generous whitespace.
- Layout: single page, sticky top navigation with anchor links to sections, tiles/cards for scanability, in the same section order as the resume: Summary → Education → Professional Experience → Additional Information (Skills, Certifications, Leadership).
- Responsive (works on phone), accessible (semantic HTML, sufficient contrast, keyboard focus visible).
- Static only: plain HTML/CSS, no frameworks, no external requests, so it works on GitHub Pages as-is.
- Keep language concise, action-verb bullets, numbers preserved exactly as in the resume.
