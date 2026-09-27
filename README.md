# FarmAI Ireland

**Irish farm advice is scattered across a dozen institutions and farm papers, and AI coverage is mostly hype. We believe FarmAI is the first free, independent editorial that reads it all for Irish farmers and turns it into one cited, plain-English action.**

![FarmAI Ireland](screenshot.jpg)

## Why I built it

Teagasc, the Department, ICBF, Bord Bia and the farm press all publish things a farmer needs to know. Nobody has time to read them all, least of all in calving season. FarmAI reads them, checks the source, and says what it means this week. It also tests a bigger idea: a small independent publisher can own a niche if listening, drafting and checking run as an engine and a person makes the final call.

## What's under the hood

- **Listening.** Every morning a scheduled job reads 19 farm and news feeds, Department press releases, Met Éireann warnings and farming Reddit. It keeps the top eight signals, says why each matters to a farmer, and logs scheme deadlines.
- **Topic scoring.** A weekly job scores queued topics on season, gaps across four content pillars, real search impressions, and overlap with pages already live. Only 80+ becomes a draft candidate. Plain code, no model calls.
- **Drafting behind gates.** Every draft cites at least two primary Irish sources, then passes a five-lens review (farm accuracy, fact-check, voice, usefulness, commercial integrity), an SEO and structure check, and a link check that rejects invented URLs. The engine pauses when three drafts are waiting.
- **A person publishes.** Nothing goes live automatically. Drafts publish from a private dashboard on one click.
- **Built for search and AI answers.** Each piece opens with a direct answer and carries FAQ and HowTo structured data. The site serves llms.txt, pings IndexNow, and feeds Search Console data back into scoring.
- **Live public data.** A daily job tracks the Department's scheme payments. County maps draw on 1.5 million land parcel records, 2017 to 2025.
- **One engine, many niches.** Sources, calendar, maps, audience and voice live in config. A new country or sector is a config swap, not a rebuild.

## Where it stands

- Live at [farmai.ie](https://farmai.ie): articles, guides, honest tool reviews, a farming-year calendar, free data tools and a monthly newsletter.

Source: private.

---

Built by John Robinson · [Stillbound.ai](https://stillbound.ai)
