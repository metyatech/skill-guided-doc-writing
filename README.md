# skill-guided-doc-writing

Agent skill for writing learner-facing and policy-style documents that are easy to scan, concrete enough to feel real, and persuasive enough to reduce "why do I have to do this?" friction.

It focuses on:

- visible information hierarchy
- selective emphasis instead of bolding everything
- pairing rules with examples and reasons
- turning abstract guidance into concrete, felt understanding
- making the main point obvious within a few seconds

## Canonical source

The **canonical source of truth** for this skill is the GitHub repository `metyatech/skill-guided-doc-writing`.

If you want to change this skill, **edit this repository**, then reinstall or sync it.
Do **not** treat installed copies under agent skill directories as the primary place to edit.

## Installation

```sh
npx skills add -g metyatech/skill-guided-doc-writing
```

Installed copies are **derived mirrors**, not the canonical authoring location.

## Usage

### Claude Code

```text
/guided-doc-writing
```

### Codex

```text
$guided-doc-writing
```

## When to use it

Use this skill when:

- drafting course docs, student-facing notices, or internal guides
- rewriting a page that feels like a wall of text
- adding examples and reasons to rules that feel arbitrary
- improving visual hierarchy in Markdown or MDX documents
- making a policy or instruction page understandable without extra explanation
- checking whether headings and bold text alone communicate the main point

## Core checks

Before marking a document complete, check:

- [ ] The reader can identify the main conclusion quickly
- [ ] Each section has a visible focal point
- [ ] Important rules are supported by examples and reasons
- [ ] Long paragraphs were split into shorter chunks or bullets
- [ ] Emphasis is selective rather than saturated

## License

MIT
