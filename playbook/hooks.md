# Hooks

Opening lines that make people stop scrolling. Each hook type has a label used in the `hook_type` field of posts.

## Hook types

Results from `results/2026-11-first-analysis.md` (small sample).

| Label | Description | Example from your posts | Results so far |
| --- | --- | --- | --- |
| `teaser-curiosity` | Opens a loop the reader wants closed | "This was meant to be a one-time thing..." | Best LinkedIn post (171 reactions, 27 comments) |
| `proof-number` | Leads with a striking result | "80% of this promo went to YC!" | Best X engagement rate (4.6%) |
| `hype-shoutout` | Short, enthusiastic praise of a team | "This team is the craziest of SF." | Highest X reach (243 avg impressions) |
| `personal-anecdote` | First-hand moment or detail | "I've seen this team going door to door to all the brokers in San Francisco" | Strong on both (LinkedIn 72 reactions / 23 comments; X 182 avg impressions) |
| `personal-observation` | A pattern Emile noticed | "Most of my interactions in SF are with European founders" | 48 reactions on LinkedIn |
| `announcement` | States news directly | "An article on Hexa in SF!" | Fine on LinkedIn (54), weak on X (87 avg impressions) |
| `bold-claim` | Strong general statement | "NYC marathon is exactly why the US are winning" | Mixed (14 and 58 reactions) |
| `story-timeline` | Dated sequence of events | "Early 2026: Pelagon starts inside the Hexa studio." | 20 reactions (n=1) |
| `contrarian` | Goes against common wisdom | "You need to be contrarian to back non-obvious companies." | Weak on both |
| `question` | Opens with a question | "At what time a new engineer stops being a founding engineer?" | Weakest X engagement (0.9%) |
| `one-liner` | Very short reaction, usually with media or a quote | "Ludo is right." | Average on X |
| `urgency` | Deadline-driven | "3 days left to apply" | 150 impressions on X (n=1) |

## Best performing hooks

- "This was meant to be a one-time thing..." (`posts/2026-10-20-linkedin-hacker-house-season-two.md`)
- "My best restaurant in SF doesn't take online orders" (`posts/2026-11-11-linkedin-grok-bot-restaurant-order.md`)
- "This team is the craziest of SF." (`posts/2026-10-13-x-pancake-craziest-team.md`)

## Hooks that fell flat

- "You need to be contrarian to back non-obvious companies." (`posts/2026-11-04-linkedin-vcs-and-contrarian-bets.md`)
- "At what time a new engineer stops being a founding engineer?" (`posts/2026-10-29-x-when-founding-engineer-ends.md`)

## Hooks to try

- `teaser-curiosity` on a middle-of-funnel topic (for example an out-of-home campaign teardown).
- `proof-number` on LinkedIn.

## Hook patterns from the tone references

Reusable patterns taken from Guillaume Roux-Romestaing, Harry Stebbings (LinkedIn) and Ben Cera (X); see "Tone references" in `profile/editorial-line.md`. All are untested for Emile. Give a pattern its own label in the table above once Emile has used it.

### From LinkedIn references (engagement not collected)

| Pattern | Source | Template | Example for Emile (to adapt) | Maps to label |
| --- | --- | --- | --- | --- |
| Result in time | Harry | "[Time] after [event], [striking result]." | "One week after opening applications, 250 founders had applied." | `proof-number` |
| Percentage claim | Harry | "[X]% of [group] [do/are something]." | "80% of our hacker house founders got into YC." | `proof-number` |
| Uncomfortable truths | Harry | "There are [N] uncomfortable truths about [topic] that nobody admits." | "There are 3 uncomfortable truths about moving to SF as a European founder." | `contrarian` |
| The story is wild | Harry | "The story of [company] is wild!" | "The story of Pelagon is wild!" | `teaser-curiosity` |
| I was wrong | Harry | "I was wrong about [belief]." | "I was wrong about outbound in the US." | `personal-anecdote` |
| How X really works | Guillaume | "How [insider thing] really works" | "How getting into a hacker house really works" | `teaser-curiosity` |
| POV series | Guillaume | "POV: you just [situation] (part [N])." | "POV: you just landed in SF to sell to US customers (part 1)." | `personal-anecdote` |
| How to in [year] | Guillaume | "How to [goal] in [year]" | "How to do outbound in 2026" | `bold-claim` |
| Provocation | Guillaume | "If you're not [X], you're dead." | "If you're not product-led, you won't win in the US." | `contrarian` |
| Milestone | Guillaume | "[Time] and [one thing] later - [result]." | "2 seasons and 1 house later - [result]." | `proof-number` |
| I've been wondering why | Guillaume | "I've been wondering why [observation]." | "I've been wondering why SF startups still buy billboards." | `personal-observation` |
| Money or value offer | Guillaume | "I want to [give reader something concrete]." | "I want to give 10 European founders a free month in SF." | `teaser-curiosity` |

### From Ben Cera on X (with his results)

| Pattern | Template | Ben's result | Example for Emile (to adapt) | Maps to label |
| --- | --- | --- | --- | --- |
| Number staircase | "[Milestone]. Next stop: [bigger goal]. [A → B in X weeks] / [B → C in Y weeks] / ..." | 1,148,649 impressions (outlier; promotion unknown) | Hacker house: season one, then season two, with applications and YC acceptances as the steps | `proof-number` |
| Founder one-liner | "never [do X] if [founder trait]" (under 15 words) | 123,038 impressions, 3.8% | "never move to SF without a reason to be there by Monday" | `bold-claim` |
| Worst time in history | "This is the worst time in history to [common habit]." | 113,525 impressions, 5.3% (best rate) | "This is the worst time in history to launch in Europe first." | `contrarian` |
| Expectation vs reality | "How founders think [X] works: [1, 2, 3]. Versus how it actually works:" | 74,551 impressions, 694 bookmarks | "How European founders think selling in the US works: ... Versus how it actually works:" | `teaser-curiosity` |
| Unspoken rules for outsiders | "There are unspoken rules in [place] that [outsiders] never see. One of the most important: [rule]." | 40,693 impressions, 512 bookmarks | "There are unspoken rules in SF that European founders miss. The first one: [rule]." | `personal-observation` |
| Bet my life on | "[Topic] moves I'd bet my life on:" then a numbered list | 39,943 impressions, 849 bookmarks | "Outbound moves I'd bet my life on in 2026:" | `bold-claim` |
| Colon cliffhanger | "[Result]. Here's every [thing] I tried before [result]:" then a thread | 22,122 impressions | "250 applications in a week. Here's everything we did to get there:" | `proof-number` |
| Start over today | "If I had to start over today with no [advantage], this is how I'd [goal]:" | 3,578 impressions, 96 bookmarks (posted on the day of the pull, so understated) | "If I had to move to SF again with no network, this is what I'd do:" | `teaser-curiosity` |
| All I did was | "I hit [result] in [time] and all I did was: [3 basics]" | 17,733 impressions | "250 founders applied to the hacker house in a week and all we did was:" | `proof-number` |
