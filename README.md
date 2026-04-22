# Founder Marketing Skills

Open-source marketing skills for founders who do their own marketing. Keyword research, growth strategy, social search audit, and competitor intelligence. Works with Claude Code, Codex, Cursor, and any agent that reads `SKILL.md`.

Free. MIT. No account, no API keys.

![Social Search Audit verdict on Cal AI](docs/images/audit-hero.png)

## Install

```
npx skills add ScaleBrick/founder-marketing-skills
```

That's it. The CLI installs the 4 skills into your agent's skills directory. Works with Claude Code, Codex, Cursor, Gemini CLI, Cline, OpenCode, and 40+ other agents. No account, no API keys.

## The 4 skills

| Skill | Command | What it does |
|-------|---------|-------------|
| **Social Search Audit** | `/audit` | Checks whether TikTok/Instagram search is a viable growth channel for your business. Evaluates niche competition, search demand, and content type fit. |
| **Growth Strategy** | `/strategy` | Generates a full marketing strategy: core themes, content pillars, brand voice, 20+ keywords with intent categories, and a posting plan. |
| **Keyword Research** | `/keywords` | Finds high-intent keywords people are searching on TikTok/Instagram for your niche. Categorizes by type (educational, problem-aware, tool comparison) and rates conversion potential. |
| **Competitor Audit** | `/competitors` | Audits your top 5-7 competitors across SEO, content, and social media. Identifies gaps you can exploit, positioning angles no one is claiming, and 5 specific moves you can make this week. |

## See it in action

Running `/audit` on Cal AI, the AI calorie-tracking app that hit $50M ARR in months.

![Full audit scrolling through](docs/images/audit-full.gif)

Intent breakdown across four categories, with real TikTok search URLs to verify every claim:

![Intent breakdown by category](docs/images/audit-intent-breakdown.png)

Ten keywords to start with, ranked by intent and conversion potential:

![Keyword table output](docs/images/audit-keywords-table.png)

## Real results from this method

```
╭─── PROOF ─────────────────────────────────────────────────────╮
│                                                               │
│  YC-backed AI healthcare app                                  │
│    353K views and 5,300 page visits in 47 days. $0 ad spend.  │
│                                                               │
│  AIFlyer                                                      │
│    0 to 15,000 signups in 3 months. Ranks alongside Canva     │
│    in TikTok's LLM responses for flyer-related queries.       │
│    All organic.                                               │
│                                                               │
╰───────────────────────────────────────────────────────────────╯
```

Zero ad spend across both. No marketing team.

## How it works

Each skill is a structured method stored as a `SKILL.md` file. When you run a skill, Claude (or your agent of choice) follows the method to analyze your specific business and produce actionable output.

No API keys needed. No account required. Just run the skill and get results.

The skills work best when you provide:
- Your business name and description
- Your target audience
- Your website URL (for audit and funnel skills)

## The method

One core insight: **40% of Gen Z uses TikTok and Instagram as search engines.** People type real questions into social search, and if your content shows up, that traffic is high-intent.

The framework:

1. **Find demand.** What are people searching for in your niche?
2. **Categorize intent.** Is this educational, problem-aware, or tool comparison? Each converts differently.
3. **Match content type.** Problem-aware content converts 54% better in some niches. Educational wins in others. You have to test.
4. **Focus ruthlessly.** 80% of content produces nothing. Find the 20% that works and kill the rest.
5. **Close the loop.** Track which keywords drive actual signups, not just views. Optimize on conversions, not vanity.

## Contributions welcome

PRs, bug reports, and new skills welcome. Each skill is a single `SKILL.md` file with structured prompts. Fork, add a skill, open a PR.

## Want it done for you?

These skills give you the strategy. Running the full execution (content production across 10 accounts, weekly attribution-driven optimization, campaign management) takes a full marketing team, or one AI that does it end-to-end.

That's what we built.

[**Morgan**](https://scalebrick.com?ref=founder-marketing-skills) is an AI VP of Marketing that runs the full growth loop: keyword research, content production, publishing, attribution tracking, and weekly optimization based on what's actually converting. She's driven 5,300 signups in 47 days for a YC-backed healthcare app and 15,000 signups in 3 months for AIFlyer.

[Try Morgan free for 7 days →](https://scalebrick.com/signup?ref=founder-marketing-skills)

## License

MIT. Free forever.

Built by [ScaleBrick](https://scalebrick.com?ref=founder-marketing-skills).
