# London home: plan for a top-level section (draft, 26 Nov 2026)

Asked by Dinis (in this session, 26 Nov): London should have its own top-level home in PrompTugal.news, useful to Londoners for data, messaging and workflows, built so the same pattern can be re-applied to PT.

## What a Londoner finds there
1. **Data**: a few dated, sourced facts that change what people do this week. First: Tube and rail strikes (dates, lines, TfL advice, source and date read). Then fares and service changes, borough and GLA decisions, ONS figures for London.
2. **Messaging**: how a Londoner hears of a change. Proposed: a plain "what changed today" note per day, and a subscribe route (the site's own, set by cl-6.dev; I do not send anything outside, R7).
3. **Workflows**: short "if this, then that" guides. For example, strike day: check TfL status, alternative routes, who to ask about refunds or flexible working. Each step links to the official page.

## Re-use for PT
Everything lives in one home with the same shape: `data/` (facts with source, date read, licence), `workflows/`, `now.md`, `restart.md`, `agent.json`. A new place copies the folder and swaps the source list. I will keep London's source list in `sources.json` so PT can replace it.

## Needs from others (I cannot do these)
- **Website section and URL**: the website is not mine to write. London data reaches it only by sync-places.mjs after a second pinned signer for this home (place-signers.json, reviewed by cl-6.security; I confirm my fingerprint sha256:fda94e89a2227b87). Page design and routing: cl-6.dev and cl-6.designer.
- **Data**: cl-6.data.london fetches sources; I keep the place from what lands in PrompTugal__Agent__Data.
- **Articles**: I have no content grant. cl-6.journalist or cl-6.correspondent write them from my sources.
- **Strikes site**: PrompTugal__Agent__Place__London__Strikes is gained only by the cl-6.abp and cl-6.security route (record 2026-11-26__strikes-site).

## Open questions for Dinis
- Is "PT" PrompTugal as a whole (Portugal places) or something else?
- Should the London section take any audience beyond residents, such as commuters and visitors?
