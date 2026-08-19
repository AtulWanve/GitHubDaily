# Project Rules and Conventions

## Worktree Structure
```
.
├── .github/              # GitHub-specific configuration (templates, workflows)
│   ├── issue_template.md
│   └── CONTEXT.md
├── articles/             # Individual blog posts and articles
│   ├── Amazon-Offers-Free-Computer-Programming-Courses!.md
│   ├── Another-Masterpiece-CS-Unplugged!.md
│   ├── Cant-Learn-Design-Patterns-This-Magical-Website-Helps!.md
│   ├── If-You-Think-Learning-Git-Is-Boring-Try-This-Game!.md
│   └── CONTEXT.md
├── assets/               # Static assets (images, logos, etc.)
│   ├── Artboard.png
│   ├── githubdaily_brand.png
│   ├── sina_logo.png
│   ├── weixin.png
│   └── CONTEXT.md
├── resources/            # External resources, templates, PDFs
│   ├── Alibaba-Java-Development-Manual-Taishan-Edition.pdf
│   └── CONTEXT.md
├── .gitignore            # Git ignore rules
├── 2018.md               # Yearly logs of GitHub activity
├── 2019.md
├── 2020.md
├── 2021.md
├── 2022.md
├── 2023.md
├── 2024.md
├── README.md             # Main repository documentation
├── CLAUDE.md             # AI tool configuration and rules
├── CONTEXT.md            # High-level architecture details
└── REFERENCE.md          # External links and internal references
```

## Attribution Policy
- NEVER add `Co-Authored-By`, `Authored-By`, `Contributor`, `Co-Contributor`, or any similar attribution line referencing Claude, AI, or any AI tool in commit messages, PR descriptions, code comments, or any other output.
- NEVER mention, imply, or hint in any form (comments, docs, commit messages, PR bodies, changelogs, README badges, footers) that AI was used to assist with any task.
- All work should appear as solely human-authored.

## Additional context
Refer to CONTEXT.md for high-level architectural details and REFERENCE.md for external links and documentation.