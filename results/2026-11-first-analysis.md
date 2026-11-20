# First analysis: imported posts, Oct 6 to Nov 19, 2026

Baseline analysis of the posts imported on 2026-11-20. It uses the classifications in each `posts/` file (pillar, topic, format, hook type).

## Data and caveats

| Platform | Posts imported | Period | Metrics available | Account size |
| --- | --- | --- | --- | --- |
| X | 28 original posts (plus 22 replies, not imported as files) | Oct 6 to Nov 19 | Impressions, likes, replies, reposts, quotes, bookmarks | 122 followers |
| LinkedIn | 9 posts | Oct 13 to Nov 11 | Reactions, comments | ~10,000 followers |

- Small sample: treat everything below as hunches, not rules.
- Metrics are a snapshot from 2026-11-20, so the last few days of posts are understated.
- LinkedIn impressions, shares, and saves are not public, so LinkedIn is compared on reactions and comments only.
- Pillar, topic, format, and hook type were classified from the post text; two X posts could not be classified (`topic: unclear`).
- X engagement = likes + replies + reposts + quotes + bookmarks. Engagement rate = engagement / impressions.

## Overall baseline

- **LinkedIn:** 54 reactions and 7.7 comments per post on average (median 48 reactions).
- **X:** 139 impressions and 4.5 engagements per original post on average. The 22 replies averaged 80 impressions.
- LinkedIn is where the audience is: the account is about 80 times bigger than on X and one LinkedIn post gets about as many reactions as an average X post gets impressions.

## By pillar (funnel stage)

| Pillar | LinkedIn posts | LinkedIn avg reactions / comments | X posts | X avg impressions | X engagement rate |
| --- | --- | --- | --- | --- | --- |
| `tofu-us-entrepreneurship` | 3 | 28 / 2.7 | 10 | 188 | 3.4% |
| `mofu-us-gtm` | 0 | n/a | 1 | 77 | 2.6% |
| `bofu-hexa-sf` | 5 | 66 / 7.6 (39 / 2.8 without the hacker house post) | 8 | 133 | 3.3% |
| `off-pillar` (topics `other` and `unclear`) | 1 | 72 / 23 | 9 | 98 | 2.8% |

## By topic

| Topic | Posts (LinkedIn + X) | What happened |
| --- | --- | --- |
| `hacker-house` | 1 + 4 | Best topic overall. LinkedIn "season two" post: 171 reactions, 27 comments (3x the next on-pillar post). On X, 192 avg impressions and the highest engagement rates. |
| `sf-founders` | 1 + 7 | Drives X reach: 236 avg impressions, top X post (Pancake shoutout, 436 impressions). LinkedIn Pancake pivot story: 58 reactions. |
| `hexa-news` | 2 + 0 | Solid on LinkedIn (press article 54, Pelagon 20 reactions). |
| `hexa-events` | 2 + 4 | Fine on LinkedIn (48 and 35 reactions), weak on X (74 avg impressions). |
| `general` (TOFU) | 2 + 2 | Weakest topic: 13 avg reactions on LinkedIn, 66 avg impressions and 0.8% engagement on X. The topics (VCs, NYC marathon, founding engineers, tech week) were general rather than founder-specific. |
| `european-founders` | 0 + 1 | Barely covered (one X quote post, 95 impressions), although it is central to the audience. |
| `outbound` | 0 + 1 | One X post (lowercase outreach, 77 impressions). |
| `product-led`, `ooh-campaigns`, `general` (MOFU) | 0 | Never posted. |
| `other` (off-pillar) | 1 + 7 | The Grok bot restaurant video got 72 reactions and 23 comments on LinkedIn (most comments after the hacker house post), but off-pillar posts on X averaged only 84 impressions. |

## By format

| Format | LinkedIn avg reactions / comments | X avg impressions | X engagement rate |
| --- | --- | --- | --- |
| `text-image` (LinkedIn) | 64 / 7.6 (n=5) | | |
| `text` | 31 / 2.7 (n=3) | 68 (n=5) | 1.2% |
| `video` | 72 / 23 (n=1) | 147 (n=5) | 3.3% |
| `quote-post` (X) | | 186 (n=12) | 3.6% |
| `image` (X) | | 100 (n=6) | 2.8% |

Text-only posts were the weakest format on both platforms. On X, quoting a founder's launch beat writing an original text post by almost 3x in impressions.

## By hook type

| Hook type | LinkedIn | X |
| --- | --- | --- |
| `teaser-curiosity` | 171 / 27 (n=1, best post) | |
| `proof-number` | | 152 avg impressions, 4.6% engagement (n=2, best rate) |
| `hype-shoutout` | | 243 avg impressions, 3.4% (n=4) |
| `personal-anecdote` | 72 / 23 (n=1) | 182 avg impressions, 3.8% (n=6) |
| `announcement` | 54 / 3 (n=1) | 87 avg impressions, 3.8% (n=3) |
| `personal-observation` | 48 / 4 (n=1) | |
| `bold-claim` | 36 / 4 (n=2) | |
| `contrarian` | 24 / 2 (n=2) | 61 avg impressions, 1.6% (n=3) |
| `question` | | 107 avg impressions, 0.9% (n=3) |
| `one-liner` | | 102 avg impressions, 2.9% (n=6) |

## What worked

- **Concrete proof plus a clear offer.** The hacker house season two post combined a curiosity hook, hard numbers (250 applicants in a week, OpenAI backing, 80% accepted to YC) and a call to apply. It is the best post on either platform.
- **Showing specific founders and teams.** Shoutouts with a personal detail ("I've seen this team going door to door", "worked one month under the same roof") travel furthest on X.
- **Visuals.** Posts with an image or video beat text-only posts on both platforms.

## What flopped

- **Abstract opinion pieces.** The VC incentives post (12 reactions, 0 comments) and the general contrarian and question hooks on X had the lowest engagement.
- **Off-pillar life posts on X** (plants, city videos, tool switches): low reach and no link to the goals.
- **Event announcements on X** without context: 74 avg impressions.

## Under-covered pillars and topics

- **Middle of funnel is almost empty:** 1 post out of 37, and none on LinkedIn. `product-led`, `ooh-campaigns`, and general US GTM have never been posted, although GTM is Emile's professional expertise and the main lever for the `authority` goal.
- **`european-founders`** has one post, despite European founders being one of the two target audiences.
- **Bottom of funnel dominates LinkedIn** (5 of 9 posts). It performs, but mostly thanks to one post; without it, LinkedIn BOFU averages 39 reactions.

## Learnings

Promoted to `playbook/learnings.md` as hunches (seen once or twice, to confirm).

## Changes for next month

- Publish at least one middle-of-funnel post per week on LinkedIn (product-led, out-of-home campaign teardown, outbound), with a visual.
- Test one `european-founders` post on LinkedIn.
- Reuse the hacker house structure (curiosity hook, numbers, offer) for other bottom-of-funnel posts.
- On X, keep founder shoutouts as quote posts with a personal detail; cut off-pillar life posts.
- Start recording LinkedIn impressions from the author analytics, so LinkedIn posts can be compared on reach.

## Playbook updates

- [x] `playbook/learnings.md` updated
- [x] `playbook/hooks.md` updated
- [x] `playbook/formats.md` updated
