# SkillMe

**The MCP-native catalog of Claude Agent Skills. Install skills in chat. Never copy a folder.**

Other skill directories show you a card and make you copy a folder from GitHub. SkillMe is different. It is delivered as an MCP server, so Claude browses the catalog, recommends the right skill for what you are doing, installs it, and applies it automatically the next session. You never leave the conversation.

Every skill is free and clonable on GitHub. Every skill is reviewed for security before it enters the catalog. We sell convenience, never access.

## How it works

Connect the SkillMe MCP server, then ask Claude for help with a task. Claude recommends and installs the right skill in chat, and it applies automatically the next session.

## Connect

`https://skillshelf-ten.vercel.app/api/mcp`

Transport is SSE. No auth to browse and get recommendations. Connect your account to install. The server exposes browse_skills and browse_packs to search the catalog, recommend_skills to find the right skill for a task, install_skill and install_pack to add them, get_active_skills to load what you installed, and manage_collection to build and share shelves.

## Open source

The catalog is open. Clone any skill from the repo. The skills are plain markdown and yours to keep.

---

SkillMe is independent and not affiliated with Anthropic. skillme.dev
