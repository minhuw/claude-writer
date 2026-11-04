# Claude Writer

A Claude Plugin helps writing academic papers targeting top-tier computer science conferences.

## Installation

First, add the plugin marketplace:

```bash
claude plugin marketplace add https://github.com/minhuw/claude-writer
```

Then, install the plugin:

```bash
claude plugin install research-paper-assistant
```

## Available Skills

- `/conference-reviewer` - Review papers from a conference reviewer's perspective
- `/evaluate` - Evaluate paper quality
- `/grammar-checker` - Check and fix grammar issues
- `/paper-validator` - Validate paper structure and formatting
- `/polish` - Polish and improve writing
- `/selection` - Improve selected text
- `/summary` - Summarize paper content
- `/validation` - Validate academic writing conventions

## Target Conferences

The review skills (`/paper-validator`, `/conference-reviewer`) cover systems,
networking, security, and mobile venues, plus the top computer-architecture
conferences (ISCA, MICRO, HPCA, ASPLOS). State the target venue when invoking a
skill so it applies the right review lens.
