# /last30days: AI-Powered Multi-Source Research Engine

> Source: https://github.com/mvanhorn/last30days-skill — 47,175 ⭐

## Overview

/last30days is an open-source AI agent skill that synthesizes trending information from multiple social platforms and data sources. Rather than relying on traditional search engines, it aggregates real-time engagement signals from community discussions and prediction markets.

## Core Functionality

Searches across 13+ platforms simultaneously — Reddit, X/Twitter, YouTube, TikTok, Hacker News, Polymarket, GitHub — scoring results by actual user engagement rather than editorial ranking.

**Key capabilities:**
- Entity resolution: Identifies relevant handles, subreddits, GitHub accounts, and hashtags before searching
- Cross-source clustering: Merges duplicate stories appearing across multiple platforms
- Engagement-based scoring: Ranks findings by upvotes, likes, views, and prediction market odds
- Deep content access: Full YouTube transcripts, top Reddit comments with vote counts, TikTok metrics

## Data Sources

| Source | Auth Method | Cost |
|--------|-------------|------|
| Reddit/HN/Polymarket/GitHub | None | Free |
| X/Twitter | Browser cookies or API key | Free/PAYG |
| YouTube | yt-dlp binary | Free |
| TikTok/Instagram | ScrapeCreators API | 10K free, then PAYG |
| Bluesky | App password | Free |
| Perplexity/Brave Search | API key | PAYG |

## Installation

```
/plugin marketplace add mvanhorn/last30days-skill
# or
npx skills add mvanhorn/last30days-skill -g
```

MIT licensed. 1,012 passing tests.
