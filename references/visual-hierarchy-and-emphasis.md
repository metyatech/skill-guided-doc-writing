# Visual hierarchy and emphasis

Use this reference when you need a tighter checklist than the main skill body.

## Reader tests

### 3-second scan test

The reader should be able to identify:

- the main conclusion
- the key action or rule
- the dangerous misunderstanding

from the title area, headings, callout titles, and emphasized text.

### Bold-only skim test

If someone reads only the bold text, they should still understand the page's outline and conclusion. If the bold text feels random or incomplete, revise the emphasis.

## Structure checklist

- Start with the most important point, not the history of the topic.
- Keep one section to one reader question or one decision.
- Split long paragraphs before they become walls of text.
- Prefer bullets for lists, rules, steps, comparisons, and checks.
- Place exceptions and edge cases after the main rule, not before it.

## Emphasis checklist

- Add at least one visible focal point per section.
- Add 1-2 emphasized phrases in most paragraphs.
- Use bold for conclusions, key terms, rules, and calls to action.
- Use italics for nuance or soft caution.
- Use underline sparingly for likely mistakes or risky misunderstandings when the format supports it.
- Keep supporting sentences mostly plain so the important text stands out.

## When to pair rule, example, and reason

Use the full trio when the page asks the reader to behave differently.

Examples:

- A class rule: state the rule, show an acceptable example, show an unacceptable example, explain why the rule exists.
- A process guide: state the step, show what correct execution looks like, explain what goes wrong otherwise.
- A policy page: state the requirement, show the boundary case, explain the risk or responsibility behind it.

If the page only states rules, readers may comply mechanically or resist them. If the page adds examples but no reason, readers may memorize patterns without understanding the principle. Use all three when durable understanding matters.

## Callout patterns

If the renderer supports callouts, use them to separate different reader jobs.

- `Conclusion First`: Put the takeaway the reader must remember.
- `OK Example`: Show acceptable behavior, output, wording, or structure.
- `NG Example`: Show the failure mode to avoid.
- `Why?`: Explain the reason in plain language.
- `Checkpoint`: Give a final quick self-check.

Localized equivalents are fine when the document language is not English.

Do not add callouts just to decorate the page. A callout should either accelerate scanning or isolate a different kind of content.

## Anti-patterns

- A section with no emphasis at all.
- A paragraph where every phrase is emphasized.
- Three or more dense paragraphs in a row without bullets or subheadings.
- Rules with no example when the reader is likely to misapply them.
- Examples with no reason when the reader is likely to ask "why does this matter?"
- Decorative callouts that repeat the heading without adding a new job for the reader.

## Rewrite pattern

### Weak

```md
Use generative AI appropriately. Check your work before you submit it. Be careful with sensitive information.
```

Why it is weak:

- No clear priority
- No example
- No reason
- No visible focal point

### Stronger

```md
## Conclusion First

- **You may use generative AI.**
- However, **do not submit anything that you cannot explain yourself.**

### Check Before Submission

- **Can you explain what it does?**
- **Can you explain where to fix it if it breaks?**
- **Did you avoid entering sensitive information?**

:::tip[OK Example]

- Ask AI for possible causes of an error, then narrow the cause yourself and fix it.
  :::

:::caution[NG Example]

- Submit AI-generated code without checking what it does.
  :::

:::note[Why?]

- **A submission is work you are responsible for.**
- Even natural-looking AI output can include mistakes or unnecessary logic.
  :::
```

Why it is stronger:

- The takeaway appears immediately.
- The reader can act on concrete checks.
- The rule is anchored by both examples and a reason.
- Emphasis creates a visible reading path.
