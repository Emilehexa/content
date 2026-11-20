# Posts

One markdown file per published post, starting from `_template.md`.

## Naming

```
YYYY-MM-DD-platform-slug.md
```

- `YYYY-MM-DD`: the publish date. Files then sort chronologically.
- `platform`: a label from `profile/platforms.md`, lowercase (for example `linkedin`, `x`, `instagram`).
- `slug`: 3 to 6 lowercase words, separated by hyphens, describing the post.

Examples:

- `2026-11-20-linkedin-why-i-quit-agencies.md`
- `2026-11-22-x-three-pricing-mistakes.md`

The same idea posted on two platforms gets two files.

## Frontmatter

Use the labels defined in `profile/` and `playbook/` so posts can be compared:

- `pillar` (funnel stage) and `topic` (sub-topic): from `profile/editorial-line.md`
- `goal`: from `profile/goals.md`
- `format`: from `playbook/formats.md`
- `hook_type`: from `playbook/hooks.md`

Fill in `metrics` once, at a fixed delay after publishing (for example 7 days). Leave a metric empty if the platform does not report it.

## Metric mapping per platform

| Field | X | LinkedIn |
| --- | --- | --- |
| `impressions` | Views | Impressions (only visible to the author) |
| `likes` | Likes | Reactions |
| `comments` | Replies | Comments |
| `shares` | Reposts + quotes | Reposts |
| `saves` | Bookmarks | Saves (only visible to the author) |
| `clicks` | Link clicks (only visible to the author) | Link clicks (only visible to the author) |
| `followers_gained` | Net new followers credited to the post (author analytics) | Net new followers credited to the post (author analytics) |
| `inbound_dms` | Founder DMs that mention or follow the post (counted by hand) | Same |
| `hacker_house_applications` | Applications credited to the post (tracked link or "how did you hear about us?") | Same |

The last two are Emile's authority KPIs (see `profile/goals.md`). Leave them empty when nothing can be credited to the post.

## Imported posts

Posts dated before 2026-11-20 were imported from public data on 2026-11-20 (X API for X, a public scrape of LinkedIn). Their metrics are a snapshot at import time, not at a fixed 7-day delay, so very recent posts are understated. Fields the public data does not expose are left empty. X replies were not imported as post files; they are summarised in `results/2026-11-first-analysis.md`.
