# Custom Skills for Claude Code & OpenClaw

Personal collection of skills for writing and productivity.

## Skills

### 🚴 wechat-article-writer

A skill for writing WeChat articles for 骑思光年 (SummerSnow) public account in authentic brand voice.

**Features**:
- Bilingual Chinese-English code-switching
- Conversational, authentic tone
- Photo-aware article structuring
- Built-in brand voice guidelines

**Usage**:
```bash
/wechat-article
```

See [wechat-article-writer/README.md](wechat-article-writer/README.md) for detailed documentation.

### 📰 ai-news-digest

Daily AI news digest fetching top 5 stories from both global and China sources.

**Features**:
- Automated web search for latest AI news
- Bilingual format (Chinese summaries with English terms)
- Covers global and China AI developments
- Curated highlights and source links

**Usage**:
```bash
/ai-news
```

See [ai-news-digest/README.md](ai-news-digest/README.md) for detailed documentation.

## Installation

### For Claude Code

1. Clone this repository to your `.claude/skills/` directory:
```bash
cd ~/.claude/skills
git clone https://github.com/pengq77/skills.git
```

2. Or create a symbolic link to a specific skill:
```bash
ln -s /path/to/this/repo/wechat-article-writer ~/.claude/skills/wechat-article-writer
```

### For OpenClaw

Same installation steps - skills are compatible with both Claude Code and OpenClaw.

## Development

Each skill follows the standard Claude skill structure:
- `SKILL.md` - Main skill instructions
- `README.md` - Documentation for users
- `examples.md` - Usage examples
- `references/` - Supporting materials

## License

Personal use. Feel free to adapt for your own needs.

---

Created with Claude Code 🤖
