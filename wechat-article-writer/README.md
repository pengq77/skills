# WeChat Article Writer Skill for 骑思光年

A Claude Code / OpenClaw skill for writing WeChat articles in the established brand voice of 骑思光年 (SummerSnow).

## Purpose

This skill helps you write new articles that match the authentic, conversational, bilingual voice of your WeChat public account. It ensures consistency in tone, language style, and content structure across all articles.

## How to Use

### In Claude Code

```bash
/wechat-article-writer
```

Then tell Claude what you want to write about, for example:
- "I want to write about my bike trip to Mount Rainier last weekend"
- "Write an article about setting up my new smart trainer"
- "Help me write about commuting by bike in winter"

### In OpenClaw

Same usage - invoke the skill and describe your topic.

## What This Skill Does

1. **Reads your brand voice guidelines** from `.claude/brand-voice-guidelines.md`
2. **Asks clarifying questions** about your topic, experience, and details
3. **Structures your article** following the established template
4. **Applies voice rules** including:
   - Natural Chinese-English code-switching
   - Conversational tone and short paragraphs
   - Self-deprecating humor
   - Practical details in personal narrative
5. **Creates title and photo captions** in your style
6. **Ensures quality** against the brand voice checklist
7. **Runs an independent authenticity review** as the final gate:
   - Human reader plausibility check
   - AI-trace risk scan and targeted rewrites
   - Explicit uncertainty note (no guaranteed detector bypass claims)

## Files in This Skill

- `SKILL.md` - Main skill instructions for Claude
- `examples.md` - Real examples from your articles for reference
- `README.md` - This file, documentation for you

## Related Resources

- `.claude/brand-voice-guidelines.md` - Complete brand voice documentation
- `brand-voice-discovery-report.md` - Original analysis of your writing
- `samples/` - Your original PDF articles

## Tips for Best Results

1. **Be specific** about the experience you want to write about
2. **Provide details**: dates, distances, locations, specific gear/tech
3. **Mention photos**: Tell Claude what photos you have or plan to include
4. **Review and refine**: The skill gives you a draft - refine it to make it fully yours
5. **Keep it authentic**: If something doesn't sound like you, adjust it

## Topic Ideas

The skill works best for articles about:
- Cycling adventures and routes
- Bike gear, setup, and maintenance
- Commuting and multimodal transit
- Tech projects and AI tools
- Cross-cultural observations (China-US)

## Example Invocations

**Example 1**: Cycling trip
```
/wechat-article-writer

I rode from Seattle to Tacoma along the Green River Trail last Saturday,
about 80km round trip. Started at 7am, took a coffee break at the halfway
point, and got back by 2pm. Beautiful fall weather.
```

**Example 2**: Tech project
```
/wechat-article-writer

I just finished setting up a new mini PC for my home server. Spent the
whole weekend figuring out Docker configs and Tailscale. Finally got
it working but made a lot of dumb mistakes along the way lol
```

**Example 3**: Gear review
```
/wechat-article-writer

I've been riding my gravel bike for 6 months now and want to write about
why it's become my only bike. Used it for commuting, weekend long rides,
even some light mountain biking. Super versatile.
```

## Customization

If you want to adjust the voice over time:
1. Update `.claude/brand-voice-guidelines.md` with new rules
2. Add new examples to `examples.md`
3. The skill will automatically use the latest guidelines

---

**Created**: 2026-03-18
**Version**: 1.1
**Author**: Built from 5 sample articles and brand voice analysis
