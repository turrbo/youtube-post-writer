# YouTube Post Writer

Generate authentic YouTube content (scripts, titles, descriptions, community posts, comment replies) using an 8-phase emotion-first system that simulates the mental state of real creators. Detects and eliminates AI-generated language patterns while adapting to YouTube's unique format requirements - spoken-word authenticity for scripts, CTR-optimized titles, SEO-rich descriptions, and retention-focused hooks. Use when creating any YouTube content that needs to sound naturally human, whether for video scripts (talking-to-camera style), written descriptions, community engagement, or thumbnail text. Particularly valuable for avoiding the "AI voice" that viewers immediately recognize in YouTube content.

## What this repo contains

- `SKILL.md` — the primary agent skill definition and workflow.
- `references/` — supporting playbooks, platform rules, examples, or data used by the skill.

## Use cases

- **Video scripts** (tutorials, reviews, vlogs, essays, comparisons, shorts)
- **Titles** that balance CTR with authenticity
- **Descriptions** with proper SEO, timestamps, and link structure
- **Community posts** for subscriber engagement
- **Comment replies** that maintain channel voice
- **Thumbnail text** that supports the title without being redundant

## Reference material

- `references/examples.md`
- `references/video-formats.md`
- `references/tool-mentions.md`
- `references/communities.md`
- `references/claude-isms.md`

## Installation

Copy this repository or the skill directory into your agent's skills directory, then load the skill by name when the task matches its use case.

```bash
# example
cp -R youtube-post-writer ~/.claude/skills/youtube-post-writer
```

## Repository layout

```text
references/
  claude-isms.md
  communities.md
  examples.md
  tool-mentions.md
  video-formats.md
LICENSE
SKILL.md
```

## Notes

The root README summarizes the live repository contents. The complete operational instructions remain in `SKILL.md`.
