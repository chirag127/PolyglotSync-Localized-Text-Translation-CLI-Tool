# Contributing to PolyglotSync-Localized-Text-Translation-CLI-Tool

Thank you for considering contributing to `PolyglotSync-Localized-Text-Translation-CLI-Tool`! We aim to maintain a high-velocity, zero-defect, and future-proof codebase.

## 1. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. Please review our [CODE_OF_CONDUCT.md](https://github.com/chirag127/PolyglotSync-Localized-Text-Translation-CLI-Tool/blob/main/CODE_OF_CONDUCT.md) to ensure you understand our expectations for participation.

## 2. Getting Started

### Prerequisites

*   **Python:** Version 3.10+ recommended. Ensure your local environment uses a modern Python distribution.
*   **uv:** The recommended package and environment manager. Install via `pip install uv` if you don't have it.
*   **Git:** For version control.

### Local Setup

1.  **Fork the Repository:** Create your own fork of the `chirag127/PolyglotSync-Localized-Text-Translation-CLI-Tool` repository.
2.  **Clone Your Fork:**
    bash
    git clone https://github.com/chirag127/PolyglotSync-Localized-Text-Translation-CLI-Tool.git
    cd PolyglotSync-Localized-Text-Translation-CLI-Tool
    
3.  **Create a Virtual Environment (Recommended):
    bash
    uv venv
    source .venv/bin/activate
    
4.  **Install Dependencies:**
    bash
    uv pip install -r requirements.txt
    uv pip install -r requirements-dev.txt # For development tools like pytest, ruff
    
5.  **Verify Installation:** Run the help command to ensure the CLI is accessible:
    bash
    polyglot-sync --help
    

## 3. Development Workflow

### Branching Strategy

*   **`main`:** The stable, production-ready branch.
*   **Feature Branches:** Create branches for new features or bug fixes from `main` using the following pattern: `feat/<feature-name>`, `fix/<bug-description>`.
    *   Example: `git checkout -b feat/add-google-translate-support`

### Making Changes

1.  **Code:** Implement your changes, adhering to the project's architectural patterns (Modular Monolith) and coding standards.
2.  **Linting & Formatting:** Ensure your code is clean and formatted:
    bash
    ruff check .
    ruff format .
    
3.  **Testing:** Write comprehensive unit and/or integration tests for your changes. Run all tests:
    bash
    pytest
    
4.  **Commit:** Commit your changes with clear, concise messages.
    bash
    git add .
    git commit -m "feat: Implement advanced NLP for text translation"
    
5.  **Push:** Push your feature branch to your fork:
    bash
    git push origin feat/add-advanced-nlp
    

## 4. Pull Requests (PRs)

*   **Target Branch:** Open your Pull Request against the `main` branch of the `chirag127/PolyglotSync-Localized-Text-Translation-CLI-Tool` repository.
*   **Description:** Provide a clear and detailed description of your changes, including:
    *   The problem your PR solves.
    *   The solution implemented.
    *   How to test your changes.
    *   Screenshots or examples if applicable.
*   **CI Checks:** Ensure all CI checks (linting, testing, build) pass before submitting.

## 5. Project Standards & Principles

*   **Architecture:** Modular Monolith.
*   **Language:** Python 3.10+.
*   **Core Tools:** uv (package management), Ruff (linting/formatting), Pytest (testing).
*   **Principles:** Adhere to SOLID, DRY, and YAGNI principles.
*   **NLP:** Leverage modern NLP patterns for translation efficiency.

## 6. Reporting Issues

If you encounter a bug or have a feature request:

1.  **Search Existing Issues:** Check if a similar issue has already been reported.
2.  **Create a New Issue:** If not, open a new issue using the provided templates (`bug_report.md`).
3.  **Provide Details:** Include steps to reproduce the bug, expected vs. actual behavior, environment details (OS, Python version), and any relevant logs or error messages.

## 7. Security

*   Report any security vulnerabilities privately to `chirag.dev@example.com` or via [SECURITY.md](https://github.com/chirag127/PolyglotSync-Localized-Text-Translation-CLI-Tool/blob/main/SECURITY.md).
*   Do not disclose vulnerabilities publicly until they have been addressed.

Thank you for contributing to `PolyglotSync-Localized-Text-Translation-CLI-Tool`!
