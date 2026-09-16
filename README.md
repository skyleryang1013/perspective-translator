# Perspective Translator

A Codex skill for turning a confusing conversation or event into a clearer map of:

- observable facts
- the user's current interpretation
- plausible alternative perspectives
- the meaning gap between them
- decision-relevant unknowns
- one high-value follow-up question

It accepts text, up to five user-attached screenshots, and relevant relationship context from the conversation. When relationship status or purpose is missing and would change the reading, it asks a few focused questions first. It preserves user-provided MBTI and other background as low-weight context rather than deleting it, does not claim to read minds, and does not diagnose people.

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
