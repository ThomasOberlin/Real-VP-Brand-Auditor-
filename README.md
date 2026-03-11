# VeriPura Brand Auditor

VeriPura Brand Auditor is a static browser-based review tool for checking websites, documents, and written content against the VeriPura Brand Style Book.

It is designed for simple GitHub Pages deployment with no backend.

## Core Functions

The auditor supports:

- upload of `.txt`, `.md`, `.html`, `.htm`, `.pdf`, and `.docx`
- public website URL review
- rule-based brand compliance scoring
- highlighted violations
- suggested corrective changes
- export of audit reports in Markdown
- export of audit reports in Word-compatible `.doc` format

## What It Reviews

The current rule set checks for likely violations in the following areas:

- tone of voice
- hype or off-brand language
- compliance-language density
- CTA language
- typography signals
- approved palette usage
- metadata completeness
- accessibility cues
- structural brand discipline

This makes it useful for reviewing:

- website pages
- investor decks
- one-pagers
- proposals
- pilot programme documents
- partner programme documents
- case studies
- email copy

## Important Operating Note

This tool is a first-pass compliance checker. It does not replace final human review.

Manual review is still required for:

- logo misuse
- exact spacing and clear-space issues
- imagery quality and tone
- deep layout quality
- precise visual hierarchy
- nuanced editorial judgment

## Project Structure

Minimal deployment structure:

```text
/
├── index.html
├── README.md
├── LICENSE
└── CHANGELOG.md
