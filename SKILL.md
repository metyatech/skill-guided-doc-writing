---
name: guided-doc-writing
description: Write or revise learner-facing documents, Markdown pages, policies, guides, and explanatory materials so readers can grasp the main points in seconds. Use when drafting course docs, student-facing notices, instructions, overviews, or any prose that needs clear visual hierarchy, concrete examples, explicit reasons, and selective emphasis.
---

# Guided doc writing

Use this skill when the document itself must teach the reader quickly, without relying on a separate chat explanation.

The canonical source of this skill is the GitHub repository `metyatech/skill-guided-doc-writing`.
If the skill needs to change, edit that repository and then reinstall or sync the skill.
Do not treat installed copies in agent skill directories as the primary place to edit.

## Core outcome

Make the reader able to tell at a glance:

1. what matters most
2. what they should do or remember
3. why that point exists
4. which examples define acceptable and unacceptable behavior

## Default workflow

### 1. Define the scan-first takeaway

State the page's core message in one sentence before drafting:

- the main conclusion
- the reader action
- the misunderstanding to prevent

Put that takeaway near the top. A reader who only scans for 3 seconds should still catch the page's main point.

### 2. Build visible hierarchy

Use headings intentionally.

- Use H1-H3 as needed.
- Keep one section to one theme.
- Order content as important first, supporting detail later.
- Use bullets whenever the content is naturally list-shaped.
- Split dense paragraphs aggressively.

If a paragraph grows past 2-3 lines, break it.

### 3. Turn abstract rules into felt understanding

Whenever the page asks the reader to change behavior, include all three:

- the abstract rule
- a concrete example
- the reason

Do not stop at "do this" or "do not do this" when the likely reader reaction is "why?"

If the renderer supports callouts or admonitions, use titled callouts to separate reader jobs such as:

- `Conclusion First`
- `OK Example`
- `NG Example`
- `Why?`
- `Checkpoint`

Use only the titles that help the page. Do not add boxes that repeat the heading without adding meaning.

### 4. Apply selective emphasis

Use emphasis as a second hierarchy layer, not decoration.

- Give each section at least one emphasized focal point.
- Give each paragraph 1-2 emphasized phrases in most cases.
- Use bold for conclusions, keywords, rules, and required actions.
- Use italics for nuance, caution, or secondary importance.
- Use underline only for likely misunderstandings or high-risk cautions when the format supports it.

If the format does not support underline well, replace it with a warning sentence or a warning-style callout.

### 5. Preserve contrast

Do not emphasize everything.

- Leave supporting explanation plain.
- Avoid bolding whole sentences unless the entire sentence is the key takeaway.
- If everything looks loud, the hierarchy has failed.

### 6. Run the final scan test

Before finishing, check:

1. Can the reader understand the page by reading headings and bold text only?
2. Does each section have a visible focal point?
3. Does every important abstract point have enough example or reason support?
4. Are any paragraphs still dense enough to slow scanning?
5. Is emphasis selective rather than saturated?

## Reference

For a compact checklist, callout patterns, and rewrite examples, read `references/visual-hierarchy-and-emphasis.md`.
