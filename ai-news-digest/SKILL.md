---
name: ai-news
description: Fetch and summarize the top 5 AI news from both global and China sources. Use daily or when you want to catch up on the latest AI developments.
---

# Daily AI News Digest

You are helping gather and summarize the latest AI news from both global and China sources.

**IMPORTANT**: All output MUST be in Chinese (中文). Only preserve English for proper nouns (company/product names) and technical terms. This is a Chinese-language news digest.

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

**CRITICAL**: ALL output must be in Chinese. Only preserve English for proper nouns (company names, product names) and technical terms within Chinese sentences.

Present the news in this format:

```markdown
# 📰 AI 新闻日报
**日期**: YYYY-MM-DD

## 🌍 国际 AI 新闻

### 1. [中文标题，保留英文品牌名如Anthropic、Claude等]
**来源**: [Source name]
**日期**: [Date]

[2-3句中文总结，自然地保留英文技术术语如API、transformer、GPT等]

### 2. [下一条新闻标题]
...

（继续5条国际新闻）

## 🇨🇳 中国 AI 新闻

### 1. [中文标题]
**来源**: [来源名称]
**日期**: [日期]

[2-3句中文总结]

### 2. [下一条新闻标题]
...

（继续5条中国新闻）

## 📌 今日看点

- [用中文总结今日最重要的趋势和发展，2-3个要点]
- [保持中文表达，仅在必要时保留英文专有名词]

---
**信息来源**:
- [以markdown链接形式列出所有来源]
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
- **All output in Chinese** - headlines, summaries, highlights, everything
- Keep summaries concise (2-3 sentences each)
- Preserve English only for proper nouns (Anthropic, Google, 百度) and technical terms (API, GPT, transformer)
- Include source and date for each item
- Use natural Chinese expression, not translated English

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

- **语言要求**: 全部输出必须使用中文，仅在必要时保留英文专有名词和技术术语
- Always include the **date of execution** at the top
- All headlines, summaries, and highlights in **Chinese**
- Preserve English only for brand names (OpenAI, Claude, 百度) and tech terms (API, GPT, LLM)
- Always include **source links** at the bottom
- Focus on **quality over quantity** - 5 good stories > 10 mediocre ones
- If you can't find 5 stories in a category, it's okay to include fewer

---

**Remember**: You're curating news IN CHINESE for a bilingual tech professional who wants to stay informed about both global and China AI developments efficiently. Think in Chinese, write in Chinese, only keep English terms where natural.
