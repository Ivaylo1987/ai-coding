# Hands-on AI

Practical, interactive guides for building with AI — each one a self-contained deep dive you can read, share, and reference.

## Guides

| Guide | Description | Link |
|-------|-------------|------|
| **[Building Skills for Claude](./docs/guides/skills/)** | 7-chapter journey from zero to production skill. Covers structure, writing, patterns, testing, and distribution. | [View guide →](https://ivaylo1987.github.io/hands-on-ai/guides/skills/) |
| **[CCA Prep Guide](./docs/guides/cca/)** | Practical study guide for the Claude Certified Architect exam. Courses, docs, projects, and checklists mapped to all 5 domains. | [View guide →](https://ivaylo1987.github.io/hands-on-ai/guides/cca/) |
| *More coming soon* | | |

## How this repo works

```
hands-on-ai/
├── docs/                    # GitHub Pages serves ONLY this folder
│   ├── index.html           # Landing page
│   ├── 404.html             # Custom 404
│   └── guides/
│       ├── skills/
│       │   └── index.html
│       └── cca/
│           └── index.html
├── reference/               # Personal notes, PDFs, images — NOT published
├── README.md
└── LICENSE
```

- **`docs/`** — public guides, served via GitHub Pages. Add a new guide = add a new folder under `docs/guides/`.
- **`reference/`** — reference material (PDFs, images, notes). Stored in the repo but not served publicly.

No build step, no deploy pipeline.

## Future topics

Some ideas for future guides:
- Building MCP
- Tools building and selection
- Claude Code augmented development
- AI-assisted reviews
- Agent architecture patterns

## About

Built by Ivaylo Hristov — engineering leader exploring how AI changes the way we build software.

Guides are based on official documentation from Anthropic and other AI providers. All materials are fact-checked against the latest official docs at the time of creation.
