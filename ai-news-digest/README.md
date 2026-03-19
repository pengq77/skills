# AI News Digest Skill

A Claude Code / OpenClaw skill for fetching and summarizing the latest AI news from both global and China sources.

## Purpose

Stay informed about AI developments with a daily curated digest of the top 5 stories from:
- 🌍 **Global AI news**: International developments, major companies, research breakthroughs
- 🇨🇳 **China AI news**: Chinese AI companies, policies, and innovations

## How to Use

### In Claude Code / OpenClaw

```bash
/ai-news
```

That's it! The skill will automatically:
1. Search for the latest AI news from global sources
2. Search for the latest AI news from China sources
3. Curate the top 5 stories from each category
4. Present them in a clean, bilingual format with summaries

## Output Format

You'll receive a structured digest with:
- **Date**: When the digest was generated
- **Global AI News**: Top 5 international stories with Chinese summaries
- **China AI News**: Top 5 China-specific stories with Chinese summaries
- **Highlights**: Key takeaways from today's news
- **Sources**: All source links for further reading

## Use Cases

### Daily Routine
```bash
# Morning catchup
/ai-news
```

### Weekly Review
```bash
# Get a broader view
/ai-news
# Then ask: "Can you highlight the major trends from this week?"
```

### Before Meetings
```bash
# Quick prep
/ai-news
# Then ask: "Anything about [specific company/topic]?"
```

### Research Context
```bash
# Gather background
/ai-news
# Then ask: "Can you expand on the [specific story]?"
```

## What You'll Get

Each news item includes:
- **Headline**: Clear, descriptive title
- **Source**: Publication name
- **Date**: When it was published
- **Summary**: 2-3 sentence overview in Chinese (with English technical terms preserved)

## News Sources Covered

### Global Sources
- TechCrunch, The Verge, Bloomberg
- MIT Technology Review, VentureBeat
- AI company blogs (OpenAI, Anthropic, Google, etc.)
- Industry publications

### China Sources
- 36kr (36氪), 机器之心, 量子位
- 新智元, AI前线
- Chinese tech companies (百度、阿里、腾讯、字节)
- Chinese AI research institutions

## Tips for Best Results

1. **Run daily**: AI news moves fast, daily updates keep you current
2. **Combine with questions**: After getting the digest, ask follow-up questions
3. **Save important digests**: Copy to your notes for future reference
4. **Share with team**: Great for team updates or newsletters

## Customization

Want to customize? You can modify the skill to:
- Focus on specific topics (e.g., only model releases)
- Change the number of stories (more or fewer than 5)
- Add specific sources you prefer
- Filter by company or technology

Just ask Claude to adjust after invoking `/ai-news`.

## Example Output Preview

```
# 📰 AI 新闻日报 | Daily AI News Digest
**日期 Date**: 2026-03-18

## 🌍 国际 AI 新闻 | Global AI News

### 1. Anthropic Releases Claude 4.6 with Enhanced Reasoning
**来源 Source**: TechCrunch
**日期 Date**: 2026-03-18

Anthropic今天发布了Claude 4.6，这是迄今为止最强大的模型版本。
新版本在推理能力、代码生成和多语言支持方面都有显著提升。
该模型现已通过API向所有用户开放。

...
```

## Automation Ideas

### Daily Digest Hook (Advanced)
You can set up a Claude Code hook to automatically fetch news each morning:

```bash
# Add to ~/.claude/hooks/daily-news.sh
#!/bin/bash
# Run at 8am daily
if [ $(date +%H) -eq 8 ]; then
    echo "/ai-news" | claude
fi
```

### Save to File
Ask Claude to save the digest:
```
/ai-news
# Then: "Save this digest to ~/ai-news/2026-03-18.md"
```

## Updates

This skill uses web search, so it automatically gets:
- ✅ Latest news (always current)
- ✅ Real-time developments
- ✅ Most recent announcements
- ✅ Breaking stories

No manual updates needed!

## Language

- News summaries: Chinese (中文)
- Technical terms: Preserved in English (Claude, API, GPT, transformer, etc.)
- Sources: Listed in original language

Perfect for bilingual tech professionals who want efficient, comprehensive AI news coverage.

---

**Created**: 2026-03-18
**Version**: 1.0
**Compatible with**: Claude Code, OpenClaw
