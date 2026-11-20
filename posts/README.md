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

- `pillar`: from `profile/editorial-line.md`
- `goal`: from `profile/goals.md`
- `format`: from `playbook/formats.md`
- `hook_type`: from `playbook/hooks.md`

Fill in `metrics` once, at a fixed delay after publishing (for example 7 days). Leave a metric empty if the platform does not report it.
