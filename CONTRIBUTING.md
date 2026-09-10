# Contributing to Awesome Agent Skills

Thank you for your interest in contributing! This guide will help you add new skills to our curated list.

## 🎯 How This Project Works

This repository uses an **auto-updated tracker** that runs every 15 minutes via GitHub Actions. The tracker (`tracker.py`) automatically discovers and catalogs AI agent skill repositories from GitHub based on specific criteria.

**You typically don't need to manually add skills** — the tracker keeps itself current by scanning for repositories with the `agent-skills` topic.

## 📋 When to Contribute

While most skills are auto-discovered, contributions are welcome for:

- **Bug fixes** — Data source errors, incorrect metadata
- **Feature suggestions** — New columns, filters, or tracker improvements
- **Documentation** — Improving this guide or README
- **Manual additions** — Skills that don't use the `agent-skills` topic but should be included

## 🚀 Adding a New Skill

### Method 1: Auto-Discovery (Recommended)

The simplest way to get your skill listed is to ensure your repository meets these criteria:

1. **Add the `agent-skills` topic** to your GitHub repository
2. **Push recent updates** — The tracker sorts by `updated-desc`
3. **Include a clear description** — This becomes the table summary

Your skill will appear in the next 15-minute update cycle automatically.

### Method 2: Manual Submission

If your skill doesn't use the `agent-skills` topic but should be included:

1. **Open an issue** describing the skill and why it should be added
2. Or submit a PR adding the entry to `data/items.json` following the format below

## 📁 Data Format

Each skill in `data/items.json` follows this structure:

```json
{
  "id": "owner/repo-name",
  "name": "owner/repo-name",
  "url": "https://github.com/owner/repo-name",
  "stars": 42,
  "language": "Python",
  "description": "A brief description of what this skill does",
  "updated_at": "2026-05-24T12:00:00Z"
}
```

### Field Descriptions

| Field | Type | Description |
|-------|------|-------------|
| `id` | string | Unique identifier, typically `owner/repo-name` |
| `name` | string | Full repository name for display |
| `url` | string | GitHub repository URL |
| `stars` | integer | Star count (auto-updated by tracker) |
| `language` | string | Primary language or `"—"` if none |
| `description` | string | Short description (max 120 chars, truncated by tracker) |
| `updated_at` | string | ISO 8601 timestamp of last push |

## 🔧 Development Setup

If you want to run the tracker locally:

```bash
# Clone the repository
git clone https://github.com/linny006/awesome-agent-skills.git
cd awesome-agent-skills

# Install dependencies
pip install -r requirements.txt  # httpx

# Run the tracker (requires GITHUB_TOKEN for higher rate limits)
export GITHUB_TOKEN=your_token_here
python tracker.py
```

## 📝 Pull Request Guidelines

### For Documentation Changes

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-change`
3. Make your changes
4. Submit a PR with a clear description

### For Data Corrections

1. Fork the repository
2. Edit `data/items.json` with the corrected data
3. Update the README table if necessary (or let the tracker regenerate it)
4. Submit a PR explaining the correction

## 🐛 Reporting Issues

Found a bug or incorrect data? Please open an issue with:

- **For data errors:** The specific repository and what's wrong
- **For tracker bugs:** Steps to reproduce and expected behavior
- **For feature requests:** Clear use case and proposed solution

## 📜 Code of Conduct

- Be respectful and constructive
- Focus on improving the quality of the list
- Help others understand the ecosystem better

## 🔗 Resources

- [GitHub Topics Documentation](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/classifying-your-repository-with-topics)
- [GitHub Search API](https://docs.github.com/en/rest/search)
- [Issue #2 — Contribution Guide Discussion](https://github.com/linny006/awesome-agent-skills/issues/2)

---

**Questions?** Open an issue and we'll help you out!
