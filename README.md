# AI-SDLC DevOps Playbook

DevOps strategy for AI-assisted software delivery at **Dhwani RIS**.

> Live site: **https://dhwani-ankit.github.io/ai-sdlc-devops/**

## What's in this repo

A single-page strategy document outlining how DevOps operates inside the AI-SDLC lifecycle at Dhwani RIS — covering four pillars:

1. **AI-Aware Code Analysis** — replacing "lint + push" with a layered pipeline that assumes the author may have been an LLM.
2. **Self-Service Environments** — staging and UAT on demand, with defined SLAs/SLOs.
3. **Pre-Go-Live Gate** — portal-driven release readiness anchored on Kotwal (CERT, pen test, OSS vulnerability scans).
4. **Post-Deployment Operations** — default-on observability and automated weekly/monthly reports.

Plus a 16-week roadmap and a list of open questions for the team.

## Structure

```
.
├── index.html              # The plan, rendered
├── assets/
│   └── css/styles.css      # Dhwani-branded stylesheet
└── .nojekyll               # Disable Jekyll on GitHub Pages
```

## Local preview

The site is plain HTML and CSS — no build step. Open `index.html` directly, or serve the directory:

```bash
python -m http.server 8000
# then http://localhost:8000
```

## Editing the plan

`index.html` is the source of truth. Edit it, commit, push — GitHub Pages redeploys automatically.

For non-trivial changes, open a PR so reviewers can comment section by section.

## Owner

Ravi Jangir — DevOps, Dhwani RIS · `ravi.jangir@dhwaniris.com`

Status: **Draft v0.1** · last updated 2026-05-14
