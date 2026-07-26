---
name: secure-api-keys-skill
description: "Store, permission-lock, and VET API keys for a project and wire them into"
version: 1.0.0
author: Community
license: MIT
platforms: [linux, macos, windows]
tags: [devops]
---

# Secure Api Keys - Skill

Store, permission-lock, and VET API keys for a project and wire them into

## Install

```bash
cp -r <skill-name> ~/.hermes/skills/devops/secure-api-keys/
```

## Usage

Invoke your AI agent with a clear instruction matching this skill's purpose. Examples:

- *"Use this skill to <primary task>"*
- *"Load devops/secure-api-keys and <do something>"*

Replace `<primary task>` with the actual task this skill performs.

## Safety & data rules

- Never commit private keys, seed phrases, API tokens, or personal data to version control.
- Use placeholders (`<YOUR_...>`) in all examples.
- Read the full README.md in this repo for advanced usage, API reference, and step-by-step workflows.

## Notes

- Keep credentials out of chat history and source control.
- Validate all outputs before acting on them.
