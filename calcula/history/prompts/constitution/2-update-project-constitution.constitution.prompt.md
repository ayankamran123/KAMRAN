---
ID: 2
TITLE: update project constitution
STAGE: constitution
DATE_ISO: 2025-11-23
SURFACE: agent
MODEL: gemini-pro
FEATURE: none
BRANCH: main
USER: ayan
COMMAND: /sp.constitution
LABELS: ["constitution", "update"]
LINKS:
  SPEC/TICKET/ADR/PR: null
FILES_YAML:
  - .specify/memory/constitution.md
TESTS_YAML: []
---

/sp.constitution

Project principles and standards:
- Write tests first (TDD approach)
- Use Python 3.12+ with type hints everywhere
- Keep code clean and easy to read
- Document important decisions with ADRs
- Follow essential OOP principles: SOLID, DRY, KISS

Technical stack:
- Python 3.12+ with UV package manager
- pytest for testing
- Keep all project files in git

Quality requirements:
- All tests must pass
- At least 80% code coverage
- Use dataclasses for data structurestry
