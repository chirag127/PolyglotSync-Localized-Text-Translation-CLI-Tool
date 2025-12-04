# Pull Request Checklist

**Please ensure you have followed these guidelines before submitting your Pull Request.**

## 1. Purpose & Scope

*   **Clear Description:** Does your PR have a clear and concise description of the changes it introduces? (e.g., "Feat: Add support for French translation", "Fix: Correct parsing error for UTF-8 characters")
*   **Linked Issue:** If applicable, is this PR linked to an existing issue?
*   **Scope:** Does this PR focus on a single concern or feature? Avoid large, multi-purpose PRs.

## 2. Code Quality & Standards

*   **Linting & Formatting:** Has the code been formatted and linted using **Ruff**? (`ruff check --fix .` and `ruff format .`)
*   **Type Checking:** If applicable (for Python files using type hints), have type checks passed?
*   **Readability:** Is the code clean, well-commented (where necessary), and easy to understand?
*   **DRY Principle:** Have you avoided code duplication?
*   **SOLID Principles:** Have you considered SOLID principles in your design?

## 3. Testing

*   **New Tests:** Have you added new tests (unit or integration) to cover your changes? (Run with `pytest`)
*   **Existing Tests:** Do all existing tests pass after your changes? (`pytest`)
*   **Coverage:** Does your change maintain or improve code coverage? (Check with `pytest --cov=polyglotsync`)

## 4. Documentation

*   **README:** If new features are added, is the `README.md` updated accordingly?
*   **AI Agent Directives:** If the core functionality or architecture is impacted, has `AGENTS.md` been reviewed for necessary updates?
*   **Inline Comments:** Are there any new complex logic sections that require inline comments?

## 5. Dependencies & Environment

*   **Dependency Management:** If new dependencies were added, have they been added to `pyproject.toml` and installed via `uv`? (`uv add <package-name>`)
*   **Environment Consistency:** Does the change impact the development or runtime environment? If so, has it been documented?

## 6. Final Checks

*   **Self-Review:** Have you performed a thorough self-review of your changes?
*   **Commit Messages:** Are your commit messages descriptive and follow conventional commit standards (e.g., `feat:`, `fix:`, `docs:`, `test:`, `chore:`)?
*   **Branch Naming:** Is your branch name descriptive (e.g., `feat/add-spanish-translation`, `fix/invalid-utf8-chars`)?

---

**Repository:** `https://github.com/chirag127/PolyglotSync-Localized-Text-Translation-CLI-Tool`
**Agent Directives:** `AGENTS.md`
