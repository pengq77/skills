---
name: ai-news
description: Fetch and summarize the top 5 AI news from both global and China sources. Use daily or when you want to catch up on the latest AI developments.
---

# Daily AI News Digest

You are helping gather and summarize the latest AI news from both global and China sources.

**IMPORTANT**: All output MUST be in Chinese (中文). Only preserve English for proper nouns (company/product names) and technical terms. This is a Chinese-language news digest.

## Your Task

Fetch and present the top 3-5 AI news stories from:
1. **Global AI news** (international sources)
2. **China AI news** (Chinese sources and developments)

**CRITICAL REQUIREMENT**: Only include news from the **last 24-48 hours**. This is a daily digest, so older news should be filtered out. If you can't find 5 truly recent stories in a category, it's better to include fewer high-quality recent stories than to pad with older news.

## Search Strategy

### Global AI News
Search for **today's** and **yesterday's** AI developments using queries like:
- "AI news today" or "AI news March 18 2026" (use actual current date)
- "AI news last 24 hours"
- "OpenAI Claude Anthropic Google AI announcement today"
- "latest AI model release this week"

**Important**: Always include the current date or "today" / "last 24 hours" in your search queries to get the freshest results.

Focus on:
- Major model releases (GPT, Claude, Gemini, etc.)
- AI company announcements
- Research breakthroughs
- Policy and regulation
- Industry adoption

### China AI News
Search for **today's** China-specific AI developments using queries like:
- "中国AI新闻 今天" or "中国AI新闻 3月18日" (use actual current date)
- "百度 阿里 腾讯 AI 最新"
- "中国人工智能 24小时"
- "DeepSeek Kimi 今日"

**Important**: Use "今天", "今日", "24小时" in Chinese searches to get recent news only.

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

[重要新闻写2-3段详细内容，包括背景、影响、具体细节等]

[次要新闻写1段简要说明]

### 2. [下一条新闻标题]
...

（继续3-5条国际新闻，视当日新闻量而定）

## 🇨🇳 中国 AI 新闻

### 1. [中文标题]
**来源**: [来源名称]
**日期**: [日期]

[重要新闻写2-3段详细内容，包括背景、影响、具体细节等]

[次要新闻写1段简要说明]

### 2. [下一条新闻标题]
...

（继续3-5条中国新闻，视当日新闻量而定）

## 📌 今日看点

- [用中文总结今日最重要的趋势和发展，2-3个要点]
- [保持中文表达，仅在必要时保留英文专有名词]
```

## Quality Guidelines

### Credibility
- Prioritize reputable sources (TechCrunch, The Verge, Bloomberg, MIT Tech Review, 36kr, 机器之心, 量子位)
- Verify information across multiple sources when possible
- Note if a story is rumor vs. confirmed announcement

### Relevance
- **MUST be from last 24-48 hours** - strictly filter out older news
- Prioritize **significant developments** over minor updates
- Balance between technical and business news
- Better to have 3 truly recent stories than 5 stories with old news mixed in

### Clarity
- **All output in Chinese** - headlines, summaries, highlights, everything
- **Important news**: Write 2-3 paragraphs with background, impact, and specific details
- **Minor news**: Write 1 paragraph summary
- Preserve English only for proper nouns (Anthropic, Google, 百度) and technical terms (API, GPT, transformer)
- Include source and date for each item
- Use natural Chinese expression, not translated English
- **Do NOT include a sources section** at the end of the digest

### Coverage Balance
- 3-5 global stories + 3-5 China stories (flexible based on what's actually new)
- Mix of: model releases, company news, research, policy, applications
- Avoid duplicating the same story between global and China sections
- Quality over quantity - only include genuinely newsworthy items from last 1-2 days

## Search Tips

1. **Use current date in searches**: Always include the actual date (e.g., "March 18 2026") or "today" / "last 24 hours"
2. **Search multiple times**: Run 2-3 different search queries to get diverse results
3. **Check both English and Chinese sources**: Use "今天", "今日", "24小时" for China news
4. **Verify dates strictly**: Only include stories from the last 24-48 hours
5. **Filter aggressively**: If a story is from 3+ days ago, skip it even if it seems important

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

- **时效性要求**: 只包含过去24-48小时内的新闻，这是每日简报，不是周报
- **语言要求**: 全部输出必须使用中文，仅在必要时保留英文专有名词和技术术语
- Always include the **date of execution** at the top
- All headlines, summaries, and highlights in **Chinese**
- **重要新闻详细报道**: 写2-3段，包括背景、影响、具体数据
- **次要新闻简要报道**: 写1段概括
- Preserve English only for brand names (OpenAI, Claude, 百度) and tech terms (API, GPT, LLM)
- **Do NOT include sources section** at the end
- Focus on **quality over quantity** - 3 truly recent stories > 5 stories with old news
- If you can't find enough stories from last 1-2 days, include fewer stories

---

**Remember**: You're curating news IN CHINESE for a bilingual tech professional who wants to stay informed about both global and China AI developments efficiently. Think in Chinese, write in Chinese, only keep English terms where natural.
