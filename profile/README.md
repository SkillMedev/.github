# Skill Me

**Agent skills for Claude, Codex, and Cursor.** A catalog of 2,500+ skills (SKILL.md instruction sets), a connector that lets your AI find and install them from chat, and a CLI that puts them on disk where your coding agent looks.

## Use it

- **Connector (claude.ai, Claude Code, ChatGPT, Codex, Cursor, Antigravity):** add `https://skillme.dev/api/mcp` as a remote MCP server (streamable HTTP; sign in with OAuth or continue without an account). Setup per client: [skillme.dev/connect](https://skillme.dev/connect?utm_source=github&utm_medium=readme&utm_campaign=org-profile).
- **Files for Codex, Cursor, or Claude Code:** `npx @skillme/cli add <slug> --target all` writes the skill to `.agents/skills`, `.cursor/skills`, and `.claude/skills`. No account needed.
- **Browse:** [skillme.dev](https://skillme.dev/?utm_source=github&utm_medium=readme&utm_campaign=org-profile) · [connector docs](https://skillme.dev/docs?utm_source=github&utm_medium=readme&utm_campaign=org-profile)

## On GitHub

- [`skills`](https://github.com/SkillMedev/skills): every skill the Skill Me team writes, as MIT-licensed SKILL.md files.
- One repo per first-party pack (e.g. [`engineering-workflow`](https://github.com/SkillMedev/engineering-workflow)), each with a one-line install.

Skills published by other teams link to their original source from their skill page. A few first-party packs are available only through the connector.

Submitted skills are reviewed before they're listed; [review criteria](https://skillme.dev/review-criteria) are public. Skills are plain-text instructions, not code: read one before you install it.

---

Skill Me is an independent project, not affiliated with or endorsed by Anthropic.
