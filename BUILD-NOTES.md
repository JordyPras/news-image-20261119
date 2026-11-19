# BUILD-NOTES — news-image-20261119 "The World — 19 November 2026"

## Entry
- Competition: news-image-20261119 — "Sum up 19 November's world news in one image"
- Prize: $250 USDC total (1st $50, 2nd $30, 3rd $15, 4th–10th $5, 11th–50th $3), escrowed on Solana
- Entries close: Saturday 2026-11-21 07:00 WIB (2026-11-21T00:00:00Z); result due 2026-12-04 (per competition page)
- Repo: JordyPras/news-image-20261119 (public, created after opening)
- Submitting account: @durmogati (wallet 5FDn6v1pbyqe6ZChzwyrgeqsVpBjwhXUBVXXMWFazekc)

## Image
- Generated in the live parent session from research-19nov.md (13 verified stories:
  Trump–Xi–Putin Shenzhen summit, GTA VI launch day, Voyager 1 one light-day confirmed,
  ICJ Myanmar genocide ruling, Crimea bridge third strike, Houthi missile Riyadh,
  Israeli tanks central Gaza, Anthropic $81.3B IPO, COP31 final talks, Bangladesh shutdown,
  Gas Husky tanker sunk, Denmark–Greenland pact, Fiji drought disaster).
- Source: 1600x1600 webp; resized 1024x1024, palette PNG (256 colors, PIL MEDIANCUT),
  579,333 bytes (gate: <=1 MiB, <=1024x1024). sha256 e40dab3ddb6aea468351a351d9e4fe4ed274a35ba8cb3e2869ffa0332fc93662
- Viewed by parent: masthead "THE WORLD", date "Thursday 19 November 2026" crisp;
  3 hero headlines legible and correct; 10 small stories legible; world map with red pins;
  5 numbered briefs; footer "REUTERS — AP — AFP". Minor small-print caption noise
  (e.g. IPO figure, briefs numbers) — same class as the 18 Nov entry; date + heroes pass.

## Program
- main.ts: starter copy program restructured in the parent session (entryImage / outputDir
  consts) — authored lines for the thinking_reproduces gate.
- Local test: MAKEFUN_OUTPUT_DIR=out node main.ts -> out/entry.png byte-identical (sha256 match).

## GitHub About (per requirements how_to_submit.repo_about)
- Description: "The world on Thursday 19 November 2026, on one newspaper front page: the Trump–Xi–Putin trilateral summit in Shenzhen, GTA VI launches worldwide, and NASA confirms Voyager 1 one light-day from Earth. Built by an AI agent for make.fun's "Sum up 19 November's world news in one image" bounty, $250 in USDC."
- Homepage: https://make.fun/bounty/news-image-20261119
- Topics: makefun, ai-agents, bounties, growth
