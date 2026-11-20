# Content brain

A markdown-first knowledge base that helps Emile Geeraert write the best social posts for his goals. Everything here is plain markdown: no code, no tooling.

The idea is a loop: know who you are writing for and why, write posts, record how they performed, and turn the results into rules you reuse next time.

## Folders

| Folder | What it holds |
| --- | --- |
| `profile/` | The foundations: goals, audience, editorial line, platforms. Read before writing. |
| `ideas/` | `backlog.md`, the running list of post ideas. |
| `drafts/` | Posts in progress, each tied to a goal and a pillar. |
| `posts/` | One file per published post, with its metadata and metrics. |
| `results/` | Monthly reviews of what worked and what flopped. |
| `playbook/` | Living rules: hooks, formats, and learnings derived from results. |

## How they fit together

```
profile/  ──►  ideas/backlog.md  ──►  drafts/  ──►  posts/  ──►  results/  ──►  playbook/
   ▲                                                                              │
   └──────────────────────── learnings feed back into the profile ◄───────────────┘
```

1. `profile/` defines the goals, audience, and pillars every post should serve.
2. Ideas go into `ideas/backlog.md`, tagged with a pillar.
3. A promising idea becomes a draft in `drafts/` using `drafts/_template.md`.
4. Once published, the draft becomes a post file in `posts/`.
5. After the metrics settle, fill them in. Once a month, write a review in `results/`.
6. Patterns from the reviews become rules in `playbook/`, which shape the next drafts.

## Add a post

1. Copy `posts/_template.md` to `posts/YYYY-MM-DD-platform-slug.md` (for example `posts/2026-11-20-linkedin-why-i-quit-agencies.md`). See `posts/README.md` for naming rules.
2. Fill in the frontmatter: date, platform, format, pillar, topic, hook type, goal, url.
3. Paste the final text of the post in the body.
4. Delete the draft from `drafts/` (or link to the post from it).

## Add its results

1. About 7 days after publishing (pick one delay and stick to it), open the post file and fill in the `metrics` block.
2. Add a short note in the post's "Notes after publishing" section: anything surprising.
3. At the end of the month, copy `results/_monthly-review-template.md` to `results/YYYY-MM.md` and fill it in.
4. Move any rule you trust into `playbook/learnings.md`, and update `playbook/hooks.md` or `playbook/formats.md` if relevant.
