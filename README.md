# decision-making

A six-phase method for big decisions (triage, frame, gather, stress-test, choose, run and review), with a review that separates a bad decision from bad luck.

A Claude skill: a folder with a SKILL.md that Claude loads when your request matches its description. Self-contained, no dependencies on other skills.

**Use it when you say:** "Help me decide...", "was that a mistake?", "I'm second-guessing this"

## Install

Clone into your personal skills directory and start a new Claude Code session:

```powershell
git clone https://github.com/liamzmind/decision-making.git "$env:USERPROFILE\.claude\skills\decision-making"
```

macOS / Linux: `git clone https://github.com/liamzmind/decision-making.git ~/.claude/skills/decision-making`

Other Claude surfaces: check the current Anthropic documentation for how skills are loaded.

## Notes

Walks you through one phase at a time, asks for written answers and ends with a decision record. It never decides for you and does not replace professional advice on medical, legal or financial specifics. Templates for a decision brief, commitment note and checkpoint review are in `references/templates.md`.

## License

MIT. See [LICENSE](LICENSE).

## Disclaimer

Independent community work, not affiliated with or endorsed by Anthropic.
