# gptsh

Minimal LLM CLI: stdin in, streamed answer out

Started as a weekend hack, grew on me.

## Examples

```bash
chatsh explain this error < error.log
cat diff.patch | chatsh review this diff
```

## Getting started

```bash
pip install -r requirements.txt
export OPENAI_API_KEY=sk-...
```

## Features

- Model and system prompt via flags or env
- Reads the prompt from args or stdin
- Works with any OpenAI-compatible endpoint
- Streams tokens as they arrive

## Project structure

```text
├── .github/
│   └── workflows/
│       └── ci.yml
├── docs/
│   ├── faq.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── tests/
│   └── test_smoke.py
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── chatsh.py
└── requirements.txt
```
