<!-- Sync Impact Report:
Version change: 1.3.0 -> 1.3.1
Rationale: Replaced the abbreviation 'OOP' with its full form 'Object Oriented Programming' for improved clarity within the 'Code Readability and OOP' principle. Updated the `Last Amended` date.
Modified principles: Code Readability and OOP (clarified abbreviation).
Added sections: None.
Removed sections: None.
Templates requiring updates:
  - ⚠ .specify/memory/constitution.md (this file itself)
Follow-up TODOs:
  - TODO(RATIFICATION_DATE): Original ratification date is unknown.
-->
# calculator-project_6 Constitution

## Core Principles

### Test-First Development
Adhere strictly to the Test-Driven Development (TDD) methodology: write tests before implementing code. Ensure all automated tests pass consistently, aiming for a minimum code coverage of 80%.

### Modern Python Stack
Utilize Python version 3.12 or higher, incorporating type hints across the codebase for enhanced clarity and maintainability. Employ the UV package manager for efficient dependency management.

### Code Readability and Object Oriented Programming
Maintain clean, readable, and well-structured code. Adhere to essential Object Oriented Programming principles like SOLID, DRY, and KISS.

### Architectural Documentation
Document significant architectural decisions, design choices, and trade-offs using Architecture Decision Records (ADRs). This ensures a clear and accessible record of project evolution.

### Tooling and Version Control
Employ pytest for unit and integration testing. All project files must be under Git version control to track changes and facilitate collaboration.

### Secure Input Handling
All user inputs must be validated to prevent injection attacks or unexpected behavior. Avoid storing or transmitting sensitive data unless absolutely necessary and protected by appropriate encryption.

### Intuitive CLI Interface
Commands should be clear, arguments well-defined, and output informative. Error messages must be actionable and guide the user towards resolution.

### Consistent Error Reporting
Implement consistent and user-friendly error handling. Exceptions should be caught, logged appropriately, and translated into clear, actionable messages for the end-user.

## Project Quality Standards

*   All automated tests must pass before merging any changes.
*   Maintain a minimum code coverage of 80%.
*   All functions must include type hints on parameters and return types (e.g., `def add(a: float, b: float) -> float:`).
*   All functions must include docstrings explaining their purpose (e.g., `"""Add two numbers and return the sum."""`).
*   Adhere to PEP 8 naming conventions, using `lowercase_with_underscores` for functions and variables.
*   Source code lines must not exceed 100 characters in length.
*   Avoid "magic numbers"; use named constants for clarity and maintainability (e.g., `MAX_RETRIES = 3` instead of `if retries < 3:`).

## Development Environment & Workflow

*   Strict adherence to Git for version control of all project files.
*   Development will occur within a Python 3.12+ environment using UV.

## Governance

All PRs/reviews must verify compliance with this constitution. Complexity must be justified. This constitution supersedes all other practices unless explicitly documented otherwise. Amendments require a clear proposal, rationale, and review process. Versioning follows semantic versioning (MAJOR.MINOR.PATCH). Compliance with this constitution is a prerequisite for code integration.

**Version**: 1.3.1 | **Ratified**: TODO(RATIFICATION_DATE): Original ratification date is unknown. | **Last Amended**: 2025-11-23