# Perspective Translator

A Codex skill for turning a confusing conversation or event into a clearer map of:

- observable facts
- the user's current interpretation
- plausible alternative perspectives
- the meaning gap between them
- decision-relevant unknowns
- one high-value follow-up question

It accepts text, up to five user-attached screenshots, and relevant relationship context from the conversation. For screenshot or relationship/communication questions, it first asks for the user's side, the relationship status, and the user's goal unless the user explicitly requests a screenshot-only reading. MBTI and other background are optional low-weight context and are never silently deleted. It does not claim to read minds or diagnose people.

## Use in Codex

Install or copy the `perspective-translator/` folder into your Codex skills directory, then invoke it with `$perspective-translator` or describe a conversation you want to understand. Attach up to five screenshots when they add context.

The skill runs inside Codex and does not require an OpenAI API key. It does not create a public API, save cases automatically, or provide multi-user authentication and rate limiting.

## Contents

```text
perspective-translator/
├── SKILL.md
└── agents/openai.yaml
```

## License

MIT. See [LICENSE](LICENSE).
