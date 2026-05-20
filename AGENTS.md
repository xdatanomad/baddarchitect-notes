# Agent Operating Guide

## Project Mission

Build a minimal, high-value website for AI architects and companies adopting AI. The site should work as a practical blueprint from strategy and operating model through production-grade AI systems, agents, security, and governance.

## Audience

- AI architects and solution architects.
- CTOs, engineering leaders, product leaders, and AI practice leaders.
- Mid-market and enterprise teams moving AI from experiments into production.
- Consultants and internal champions who need practical adoption playbooks.

## Editorial Position

Use a direct, candid, professional, and humble voice. Avoid hype, inflated claims, and "AI will solve everything" framing. The site should be practical, skeptical where needed, and useful to serious builders.

Core stance:

- AI adoption is a systems problem, not a tooling problem.
- Workflow, data, permissions, evaluation, governance, and operating model matter as much as models.
- Fear and skepticism are valid adoption inputs, not obstacles to dismiss.
- Production AI requires reliability, security, observability, evals, human review, and clear ROI.

## Approval Boundaries

- Do not delete existing files or loose content.
- Do not revise the approved project milestones without direct user approval.
- Do not add additional project skills beyond the explicitly requested frontend-design skill without direct user approval.
- Proposed changes to milestones, strategy, site architecture, or skill inventory should be written as pending proposals.
- If moving content, preserve the original text in an organized location and leave a clear pointer from the old location when practical.

## Current Content Map

- `MEMORY.md` - user preferences, identity, career context, and tone guidance. Treat as sensitive private project context; do not copy into publishable content.
- `content/notes/website.md` - early site preamble and framing around atomic AI adoption.
- `content/notes/bottlenecks.md` - major source essay on AI-native bottlenecks.
- `content/notes/NOTES.md` - raw milestone, adoption-stage, security, team, and tool notes.
- `content/notes/articles_outline.md` - article backlog and article concepts.
- `content/articles/challenges/the_fear.md` - draft article on fear as the first adoption bottleneck.
- `content/articles/challenges/02_moving_forward.md` - draft article on responsible participation with AI.
- `content/strategy/` - project metadata, milestones, phases, and architecture planning.

## Suggested Working Flow

1. Read this file.
2. Read `content/strategy/project-brief.md`.
3. Read only the source notes relevant to the task.
4. Make small, focused edits.
5. Preserve source material and separate raw notes from publishable content.
6. Add citations for factual claims that depend on external research.
7. Keep content concise and actionable.

## Content Quality Bar

Every publishable page should have:

- A clear reader and job-to-be-done.
- A concrete takeaway in the first screen.
- Practical examples, checklists, diagrams, or decision rules where useful.
- Clear separation between opinion, experience, and cited external claims.
- SEO-ready title, description, canonical slug, and internal links.
- No private personal context copied from `MEMORY.md`.

## Website Quality Bar

The website should be:

- Minimal and fast.
- Static-first where possible.
- Easy to add Markdown or MDX content to.
- Accessible, responsive, and readable on mobile.
- Structured for SEO with clean URLs, metadata, sitemap, schema where useful, and strong internal linking.
- Visually calm, credible, and not overly promotional.

## Project Skills

The local project skill inventory lives in `.agents/skills/`.

Currently added:

- `frontend-design` from Anthropic's skills repository, requested by the user.

Pending approval only:

- Additional content, SEO, AI security, or production-agent architecture skills.
