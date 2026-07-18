# SpaceShare — Docs

Central home for everything that isn't code: the PRD, research, API reference exports, Jira backlog exports, and user-facing documentation for the SpaceShare capstone project (Group 8).

---

## Contents

```
/prd/                  # Product Requirements Document (source + PDF/DOCX exports)
/research/             # Market research, competitor analysis, sourced statistics
/jira/                 # Backlog CSV exports, sprint summaries
/api/                  # Living API reference (kept in sync with spaceshare-backend)
/guides/                # Workspace Seeker guide, Host onboarding guide, Corporate Admin guide
/support/               # FAQ content, support ticket categories, refund & escalation policy
/release-notes.md       # What shipped, sprint by sprint
```

---

## Who Owns What

- **PRD, research, roadmap** — Product Management
- **API reference** — kept current by Backend, reviewed by Technical Writing
- **User guides, FAQ, release notes** — Technical Writing, in collaboration with PM and Design
- **Jira exports** — Product Management, updated after each sprint planning/review

---

## Workflow

Documentation should be updated **alongside the build**, not written from scratch at the end:

1. When an API endpoint changes, Backend flags it in the team channel; Technical Writing updates `/api/`.
2. When a new user-facing flow ships, Technical Writing drafts the relevant section of `/guides/` against the real, working feature — not the original spec — since real behavior sometimes differs slightly from the plan.
3. At the end of each sprint, export the current Jira board state into `/jira/` for submission evidence.

---

## Final Submission Checklist Mapping

This repo should contain the evidence for these submission items by the end of the project:

- Research findings, survey, and interview evidence → `/research/`
- Problem statement, target users, personas → `/prd/`
- PRD, user stories, acceptance criteria → `/prd/`
- API, tech stack, infrastructure overview → `/api/`, `/prd/`
- Jira backlog and Sprint Board exports → `/jira/`
- UAT checklist and bug log summary → `/jira/`
- Sprint Review and Retrospective summaries → `/jira/`
- Product Roadmap, North Star Metric, KPIs → `/prd/`
- Go-to-Market plan → `/prd/`
