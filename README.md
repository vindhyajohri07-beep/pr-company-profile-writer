# PR Company Profile Writer – Claude Skill

A Claude skill for PR professionals. It writes company profiles, platform listings and bylined or editorial features for tech and analytics publications (such as Analytics Insight), media houses and business directories. Every piece is aligned to brand identity and current trending topics.

## What it does

- **Company profiles:** evergreen 1–3 page profiles, with versions for investors, media, clients and talent
- **Platform listings:** media features with 50- and 150-word blurbs and directory tags
- **Articles:** first-person bylines and third-person editorial features that position the company as the pioneer in its niche
- **Topic research:** trending-topic research from free sources (Google Trends, Reddit, Quora, autocomplete), scored for brand fit
- **Brand strategy:** a Brand Identity Card, plus a choice between a brand-visibility and a brand-recognition approach
- **Competitive positioning:** positions against named competitors without ever naming them in the article
- **Publication house styles:** matches the editor's reference article, with a built-in Analytics Insight house style
- **Compliance:** follows E-E-A-T and Google's latest AI-content guidance, and checks that guidance every session

## Built-in safeguards

- Never invents facts, metrics, clients or quotes. Gaps are marked `[VERIFY]`.
- Treats the company website as the source of truth for products and features.
- Asks for the human inputs that make a piece publishable (byline, a real story, the spokesperson, client proof), and marks any gaps as `[HUMAN INPUT]`.
- Is honest about AI detectors: it doesn't promise scores, and explains that only human editing reliably lowers them.

## Install

**Claude app (web or desktop):**
1. Download this repo: **Code → Download ZIP**, then unzip it.
2. Zip only the `pr-company-profile-writer` folder.
3. In Claude, open **Settings → Capabilities → Skills**, choose **Upload skill**, and select the zip.

**Claude Code:**
```bash
git clone https://github.com/<your-username>/pr-company-profile-writer.git ~/.claude/skills/pr-company-profile-writer
```

## Usage

> "Write an author article for [Company], website [URL], for Analytics Insight. 1,500 words, positioning them as the pioneer in [niche]. Here's the editor's reference article and our decks."

Attach decks, briefs or the editor's reference article for the best results.

## Folder structure

```
pr-company-profile-writer/
├── SKILL.md
├── README.md
└── LICENSE
```

## License

MIT
