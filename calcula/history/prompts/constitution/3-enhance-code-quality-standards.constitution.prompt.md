---
ID: 3
TITLE: enhance code quality standards
STAGE: constitution
DATE_ISO: 2025-11-23
SURFACE: agent
MODEL: gemini-pro
FEATURE: none
BRANCH: main
USER: ayan
COMMAND: /sp.constitution
LABELS: ["constitution", "code-quality", "update"]
LINKS:
  SPEC/TICKET/ADR/PR: null
FILES_YAML:
  - .specify/memory/constitution.md
TESTS_YAML: []
---

Update @.specify/memory/constitution.md to improve Code Quality Standards

- All functions must include type hints on parameters and return types
  - Example: `def add(a: float, b: float) -> float:`
- All functions must include docstrings explaining what they do
  - Example: `"""Add two numbers and return the sum."""
`
- Follow PEP 8 naming conventions (lowercase_with_underscores for functions)
- Lines must be under 100 characters
- No magic numbers; use named constants
  - Bad: `if x > 10:`
  - Good: `if x > MAX_POWER_EXPONENT:`
