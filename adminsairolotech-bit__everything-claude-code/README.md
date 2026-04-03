# Everything Claude Code

[![Stars](https://img.shields.io/github/stars/adminsairolotech-bit/everything-claude-code?style=flat)](https://github.com/adminsairolotech-bit/everything-claude-code/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Top Language](https://img.shields.io/github/languages/top/adminsairolotech-bit/everything-claude-code)](https://github.com/adminsairolotech-bit/everything-claude-code)

A practical, cross-tool **agent harness performance optimization system** for modern AI coding workflows.

This repository helps you build more reliable agent-driven development using reusable skills, context/memory patterns, security-first operating practices, and research-first execution for **Claude Code, Codex, Opencode, Cursor, and related assistants**.

---

## Why this project exists

AI coding agents perform best when they run inside a strong operating system: clear task framing, high-quality context, verification loops, and explicit safety constraints.

**Everything Claude Code** provides that system so teams and individuals can ship with more confidence and consistency.

---

## Key Features

- **Agent performance optimization patterns** for common engineering tasks
- **Reusable skill packs and workflows** for consistency across projects
- **Memory/context management strategies** for long-running multi-step work
- **Security-first guardrails** for safer execution in real repositories
- **Research-first development flow** to reduce hallucinations and improve factual accuracy
- **Cross-tool compatibility** across Claude Code and adjacent AI coding tools
- **Template-driven structure** for repeatable setup and faster onboarding
- **Polyglot-ready assets** (JavaScript-first, with support patterns for other stacks)

---

## Installation

### Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) 18+ (recommended)
- npm (bundled with Node.js)

### Clone the repository

```bash
git clone https://github.com/adminsairolotech-bit/everything-claude-code.git
cd everything-claude-code
```

### Install dependencies

If a `package.json` is present:

```bash
npm install
```

If the repository is primarily templates/docs/prompts, you can skip dependency installation and start using the assets directly.

---

## Usage

Because this repository is a harness/framework, usage is modular. Start with the workflow below:

1. **Choose a target tool** (Claude Code, Codex, Cursor, Opencode, etc.).
2. **Select a skill/workflow template** relevant to your task (feature build, refactor, review, debugging, research).
3. **Inject project context** (requirements, constraints, architecture, coding standards).
4. **Apply security and verification loops** (tests, static checks, output review).
5. **Capture outcomes in memory/context artifacts** for iterative improvement.

### Suggested baseline flow

- Define task goal and acceptance criteria
- Attach minimal but sufficient context
- Run agent with constrained instructions
- Validate outputs with tests/checklists
- Record learnings and improve the next run

### Optional local scripts

If available in `package.json`, run:

```bash
npm run lint
npm test
npm run build
```

(Use only scripts that exist in the repository.)

---

## Recommended Team Adoption

- Start with one high-value workflow (e.g., bugfix or PR review)
- Standardize one skill pack per team function
- Add a mandatory verification checklist before merge
- Track failure modes and improve prompts/templates weekly

---

## Contributing

Contributions are welcome.

### How to contribute

1. Fork the repository
2. Create a feature branch:
   - `git checkout -b feat/your-change`
3. Make your changes (docs, templates, scripts, workflows)
4. Run relevant checks/tests
5. Commit with clear messages
6. Push branch and open a Pull Request

### Contribution guidelines

- Keep changes practical and reusable
- Prefer explicit, testable instructions over vague prompts
- Include examples for new workflows
- Preserve security-first and research-first principles
- Update documentation when behavior or structure changes

For major changes, open an issue first to discuss scope and design.

---

## License

This project is licensed under the **MIT License**.  
See [LICENSE](LICENSE) for details.