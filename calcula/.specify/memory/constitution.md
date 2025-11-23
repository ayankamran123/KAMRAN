<!--
## Sync Impact Report

- **Version Change**: v1.0.2 -> v1.0.3 (PATCH)
- **Rationale for Version Bump**: Added "(OOP)" shorthand to the "Object-Oriented Programming Principles" section for brevity and clarity.
- **Modified Principles**:
    - V. Object-Oriented Programming Principles (Added shorthand)
- **Added Principles**: None
- **Added Sections**: None
- **Templates Requiring Updates**:
    - ⚠ pending: `.specify/templates/plan-template.md` (Constitution Check)
    - ⚠ pending: `.specify/templates/spec-template.md` (Scope/Requirements)
    - ⚠ pending: `.specify/templates/tasks-template.md` (Task types)
    - ⚠ pending: `.specify/commands/*.md` (Agent-specific references)
    - ⚠ pending: `README.md` or other runtime docs
- **Follow-up TODOs**: None
-->
# [PROJECT_NAME] Constitution

## Core Principles

### I. Test-First (TDD)
All new code must be written according to a Test-Driven Development (TDD) approach. Tests must be written and pass *before* the implementation code is committed. Adhere strictly to the Red-Green-Refactor cycle.

### II. Python 3.12+ with Type Hints
Utilize Python version 3.12 or later. All code must incorporate type hints to enhance clarity, maintainability, and enable static analysis.

### III. Clean Code, Readability, and Maintainability
Code must be clean, well-formatted, and easy to read and understand. Prioritize simplicity and clarity over cleverness. Adhere strictly to the following:
-   **PEP 8 Naming Conventions**: Use `lowercase_with_underscores` for functions and variables, `UPPERCASE_WITH_UNDERSCORES` for constants.
-   **Line Length**: Lines must not exceed 100 characters.
-   **Type Hinting**: All functions must include type hints for parameters and return types.
    -   Example: `def add(a: float, b: float) -> float:`
-   **Docstrings**: All functions must include comprehensive docstrings explaining their purpose, arguments, and return values.
    -   Example: `"""Add two numbers and return the sum."""
`
-   **Named Constants**: Avoid "magic numbers"; define and use named constants for all literal values that have a specific meaning.
    -   Bad: `if x > 10:`
    -   Good: `if x > MAX_POWER_EXPONENT:`

### IV. Documentation through ADRs
Document significant architectural decisions, design choices, and important technical trade-offs using Architecture Decision Records (ADRs). This ensures a clear historical record of key project evolutions.

### V. Object-Oriented Programming (OOP) Principles
Adhere to fundamental OOP principles, including SOLID, DRY (Don't Repeat Yourself), and KISS (Keep It Simple, Stupid), to build robust and maintainable software.

### VI. Data Structures with Dataclasses
Employ Python's `dataclasses` module for defining data structures, promoting clarity and reducing boilerplate code.

## Technical Stack & Quality Requirements

### Technology Stack
- **Language:** Python 3.12+
- **Package Manager:** UV
- **Testing Framework:** pytest
- **Version Control:** Git (all project files must be tracked)

### Quality Requirements
- All automated tests must pass successfully.
- Maintain a minimum code coverage of 80%.

## Development Workflow & Compliance

### Compliance
- This Constitution supersedes all other development practices and informal guidelines.
- All Pull Requests (PRs) and code reviews must verify adherence to these constitutional principles and requirements.

**Version**: v1.0.3 | **Ratified**: 2025-11-23 | **Last Amended**: 2025-11-23
