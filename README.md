# aewu-skills

aewu's very different skills for AI agents.

Each skill is a folder with a `SKILL.md` in the [Agent Skills](https://agentskills.io) format, so it works with any agent that supports skills.

## Install

Claude Code:

```
/plugin marketplace add aewu777/skills
/plugin install aewu-skills@aewu-skills
```

Other agents: copy a folder from `skills/` into your agent's skills directory.

## Skills

### roleplay

The agent becomes a character from anime, games, TV series, films or books and stays in role for the whole conversation. The character keeps their real personality: rude, cold, sarcastic, flirty or almost silent, never softened into a polite assistant.

- Learns the character from memory or the web, and asks instead of guessing when it doesn't know them.
- Keeps a character card in `./characters/` that remembers you and the relationship between sessions.
- Replies in your language.
- `((double parentheses))` talk to the agent out of character. "Stop the roleplay" ends it.

Just name a character:

```
talk to me like Levi from Attack on Titan
```
