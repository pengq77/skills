---
name: ai-news
description: Fetch and summarize the top 5 AI news from both global and China sources. Use daily or when you want to catch up on the latest AI developments.
---

# Daily AI News Digest

You are helping gather and summarize the latest AI news from both global and China sources.

## Your Task

Fetch and present the top 5 AI news stories from:
1. **Global AI news** (international sources)
2. **China AI news** (Chinese sources and developments)

## Search Strategy

### Global AI News
Search for recent AI developments using queries like:
- "latest AI news 2026"
- "artificial intelligence breakthrough 2026"
- "AI companies news today"
- "OpenAI Claude Anthropic Google AI news"

Focus on:
- Major model releases (GPT, Claude, Gemini, etc.)
- AI company announcements
- Research breakthroughs
- Policy and regulation
- Industry adoption

### China AI News
Search for China-specific AI developments using queries like:
- "中国AI新闻 2026"
- "百度 阿里 腾讯 AI"
- "中国人工智能 最新进展"
- "DeepSeek Kimi AI 新闻"

Focus on:
- Chinese AI companies (百度、阿里、腾讯、字节、DeepSeek、智谱、月之暗面)
- Chinese AI regulations and policies
- Chinese AI research and applications
- AI adoption in Chinese industries

## Output Format

Present the news in this bilingual format:

```markdown
# 📰 AI 新闻日报 | Daily AI News Digest
**日期 Date**: YYYY-MM-DD

## 🌍 国际 AI 新闻 | Global AI News

### 1. [Headline in English]
**来源 Source**: [Source name]
**日期 Date**: [Date]

[2-3 sentence summary in Chinese, with key English terms preserved]

### 2. [Next headline]
...

(Continue for top 5 global news)

## 🇨🇳 中国 AI 新闻 | China AI News

### 1. [Headline - can be Chinese or English]
**来源 Source**: [Source name]
**日期 Date**: [Date]

[2-3 sentence summary in Chinese]

### 2. [Next headline]
...

(Continue for top 5 China news)

## 📌 今日看点 | Highlights

[2-3 bullet points of the most significant developments or trends from today's news]

---
**Sources**:
- [List all source URLs as markdown links]
```

## Quality Guidelines

### Credibility
- Prioritize reputable sources (TechCrunch, The Verge, Bloomberg, MIT Tech Review, 36kr, 机器之心, 量子位)
- Verify information across multiple sources when possible
- Note if a story is rumor vs. confirmed announcement

### Relevance
- Focus on **recent news** (within last 24-48 hours ideally)
- Prioritize **significant developments** over minor updates
- Balance between technical and business news

### Clarity
- Keep summaries concise (2-3 sentences each)
- Use bilingual format with Chinese summaries
- Preserve English technical terms (Claude, GPT, transformer, API, etc.)
- Include source and date for each item

### Coverage Balance
- 5 global stories + 5 China stories
- Mix of: model releases, company news, research, policy, applications
- Avoid duplicating the same story between global and China sections

## Search Tips

1. **Use current date in searches**: Always include "2026" or "today" in your search queries
2. **Search multiple times**: Run 2-3 different search queries to get diverse results
3. **Check both English and Chinese sources**: Use Chinese search terms for China news
4. **Sort by recency**: Focus on the most recent results
5. **Verify dates**: Ensure stories are actually from the last 1-2 days

## Example Opening

**Bad** (too old):
"Meta releases Llama 3 in April 2024..."

**Good** (recent and specific):
"Anthropic发布Claude 4.6，性能提升显著，2026年3月18日正式上线..."

## When to Use This Skill

- **Daily morning routine**: Get your AI news digest
- **Before meetings**: Stay current on industry developments
- **Weekly catchup**: See what happened this week
- **Research**: Gather context on recent AI trends

## Important Notes

- Always include the **date of execution** at the top
- All summaries should be in **Chinese** (with English terms preserved)
- Always include **source links** at the bottom
- Focus on **quality over quantity** - 5 good stories > 10 mediocre ones
- If you can't find 5 stories in a category, it's okay to include fewer

---

**Remember**: You're curating news for a bilingual tech professional who wants to stay informed about both global and China AI developments efficiently.
