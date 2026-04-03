# Multi-AI System Prompts Corpus

![GitHub stars](https://img.shields.io/github/stars/adminsairolotech-bit/multi-ai-system_prompts_leaks?style=flat-square)
![GitHub license](https://img.shields.io/github/license/adminsairolotech-bit/multi-ai-system_prompts_leaks?style=flat-square)
![Top language](https://img.shields.io/github/languages/top/adminsairolotech-bit/multi-ai-system_prompts_leaks?style=flat-square)
![Last commit](https://img.shields.io/github/last-commit/adminsairolotech-bit/multi-ai-system_prompts_leaks?style=flat-square)

A curated, regularly updated corpus of publicly shared and community-documented system prompts across major AI assistants, intended for research, comparison, and safety analysis.

## ⚠️ Important Notice

This repository is for **research and educational purposes**.  
Do not use this corpus to violate provider terms, exfiltrate private data, or bypass safety controls.

Because prompt provenance varies, entries may be:
- partial
- outdated
- inferred
- unofficial

Always verify before drawing conclusions.

## Coverage

Current prompt families include:

- **OpenAI**: GPT-5.4, GPT-5.3, Codex
- **Anthropic**: Opus 4.6, Sonnet 4.6, Claude Code
- **Google**: Gemini 3.1 Pro, Gemini 3 Flash, Gemini CLI
- **xAI**: Grok 4.2, Grok 4
- **Perplexity**
- Additional emerging models/tools as discovered

## Key Features

- Cross-provider prompt corpus in one place
- Organized by provider/model/version (when known)
- Plain-text artifacts optimized for search and `git diff`
- Useful for prompt engineering, model behavior analysis, and red-team/blue-team workflows
- Git history enables historical comparison of prompt evolution
- Regular updates as new public artifacts appear

## Repository Structure

The layout may evolve, but is generally organized as:

- `/<provider>/`
  - `/<model-or-family>/`
    - prompt files
    - optional metadata/source context (when available)

## Quick Start

No build step is required.

### 1) Clone

`git clone https://github.com/adminsairolotech-bit/multi-ai-system_prompts_leaks.git`  
`cd multi-ai-system_prompts_leaks`

### 2) Explore the corpus

List files:

`find . -type f | sort`

Search for keywords:

`grep -Rin "safety\|policy\|tools\|refusal" .`

Track changes over time:

`git log --stat`  
`git diff <old_commit> <new_commit>`

### 3) Optional analysis workflow

You can use your preferred scripting language (Python, shell, etc.) to:
- parse prompt files
- generate diffs across versions/providers
- extract recurring instruction patterns
- build internal evaluation datasets

## Suggested Use Cases

- Prompt engineering research
- Alignment and behavior comparison across models
- Safety policy drift analysis
- Adversarial testing and defense benchmarking
- Documentation and historical archiving

## Data Quality & Provenance

When adding or using entries, distinguish between:
- **verbatim captures**
- **reconstructions/inferences**
- **community-reported variants**

Include source context whenever possible (date, platform, capture method, link/reference if available).

## Contributing

Contributions are welcome.

### How to contribute

1. Fork the repository
2. Create a branch:  
   `git checkout -b add/<provider-model-update>`
3. Add/update prompt files in the appropriate directory
4. Include provenance notes (source context, date, confidence)
5. Commit with a clear message:  
   `git commit -m "Add Gemini 3.1 Pro system prompt variant (2026-xx-xx)"`
6. Open a pull request

### Contribution guidelines

- Keep files plain text where possible
- Preserve original formatting when known
- Avoid duplicate entries
- Mark uncertain artifacts clearly
- Do not include private, unauthorized, or personally identifiable data

## License

**No license is currently declared for this repository.**

That means reuse rights are not automatically granted.  
If you are the maintainer, consider adding a standard license (e.g., MIT/Apache-2.0) to clarify permitted use.

## Disclaimer

All trademarks and model names belong to their respective owners.  
This project is not affiliated with, endorsed by, or sponsored by any AI provider.