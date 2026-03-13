# i-have-a-dream-ai

I Have A Dream AI is a public blog documenting the development of practical AI systems.

The blog exists to share how the ecosystem is being built in public, from early architecture decisions to working automation pipelines and real developer workflows.

## Projects included

- AI Scrum Manager
- AI Content Factory
- AI Blog Engine

## Focus

- AI automation
- AI for developers
- AI-assisted workflows
- building AI systems in public

## Content structure

The repository is organized to publish updates by project area and broader ecosystem progress:

- `content/ai-scrum-manager/` for project-specific delivery and workflow posts
- `content/ai-content-factory/` for implementation and product progress updates
- `content/building-in-public/` for ecosystem-level notes, milestones, and public build logs
- `images/` for screenshots, diagrams, and post assets

## Automated Build in Public Blog

This repository now also hosts an automated GitHub Pages blog under `docs/`.

The publishing flow is driven by `ai-blog-engine`:

- `observer_agent` reads repository commits and changed files
- `analyst_agent` structures technical changes
- `story_agent` builds a narrative about engineering progress
- `blog_writer_agent` renders the final markdown
- `publishers/github_pages_publisher.py` publishes the generated post into `docs/_posts/` using Jekyll-compatible front matter

This allows the ecosystem to transform repository activity into public build-in-public posts that document both platform evolution and the developer journey.

The generated posts are designed for GitHub Pages and can be committed and pushed automatically after publication.