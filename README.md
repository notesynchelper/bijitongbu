# NoteHelper skill (笔记同步助手)

An agent skill (OpenClaw / ClawHub format) that saves articles and links to your
[NoteHelper (笔记同步助手)](https://www.bijitongbu.site/tutorials/developer-integration/) cloud notebook
and searches what you've already saved.

- Subcommands: `save`, `link`, `search`, `config`
- Only API origin: `https://claw.notebooksyncer.com`
- Requires `curl`; API key is injected as `NOTEHELPER_API_KEY` (never written to disk by the skill)
- No telemetry. Writes (`save` / `link`) always need explicit user confirmation.

Version: 1.1.0 · License: MIT-0

See [`SKILL.md`](SKILL.md) for full behavior, privacy notes and billing.
