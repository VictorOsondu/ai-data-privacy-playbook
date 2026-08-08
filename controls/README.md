# Where the AI privacy controls actually live

Every major AI tool has a switch that decides whether your conversations train the vendor's models. Finding it is the hard part. The labels differ, the menus differ, and in two cases the setting most people reach for isn't the one that controls training at all.

This section is a per-tool map: the click path, what the setting does, and — the part that matters most — what it doesn't do.

Last reviewed: 2026-08-08. See [sources and verification notes](../sources.md).

## Verification status

Each page is verified against the vendor's own documentation, and carries the date it was last checked. Anything unverified says so at the top rather than quietly reading as fact.

| Tool | Key setting | Last verified | Status |
|------|-------------|---------------|--------|
| [Claude](claude.md) | `Model Improvement` | 2026-08-08 | ✅ Verified against vendor documentation |
| [Google Gemini](gemini.md) | `Keep Activity` | 2026-08-08 | ✅ Verified against vendor documentation |
| [Microsoft Copilot](copilot.md) | `Training on conversation activity` | 2026-08-08 | ✅ Verified against vendor documentation |
| [ChatGPT](chatgpt.md) | `Improve the model for everyone` | 2026-08-08 | ⚠️ Partially verified — checked in-product on **Plus**; other plans and sub-settings still open |

**Meta AI is deliberately not covered yet.** Its controls are an objection form rather than a settings toggle, they're only available in some regions, and the reporting around them is messier than the others. A page here needs the same standard of verification as the rest, and it isn't there yet.

## The four things people get wrong

If you read nothing else in this section:

1. **Turning off training doesn't always stop human review.** Gemini keeps human-reviewed conversations for up to three years, disconnected from your account, and that survives switching the setting off.
2. **Memory and training are different settings.** In Copilot they live in two separate menus. Switching off personalisation does nothing to training, and plenty of people believe otherwise.
3. **Claude is opt-in where the others are opt-out.** If you apply a "turn it all off" habit, you'll go looking for a switch that's already in the safe position — and risk flipping it the wrong way.
4. **Paying doesn't opt you out.** ChatGPT Plus, verified in the product, has `Improve the model for everyone` **on** by default. The line that matters is consumer versus *business*, not free versus paid.

## How to use this

Work through your own tools one at a time, then record what you found in the [AI tool register](../templates/ai-tool-register.md). The register asks for a *verified* answer to "trains on inputs?" — this section is how you get it.

For the policy behind the setting, the [AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker) extension quotes the relevant clauses from a vendor's privacy policy in about two minutes. The two work together: the extension tells you what the vendor has committed to in writing, these pages tell you where the switch is.

## Why this is a maintained list and the tool map isn't

The [AI tool → data-practices map](https://github.com/VictorOsondu/ai-governance-kit/blob/main/data-map/tool-data-practices-map.md) in the governance kit is a blank template on purpose — a pre-filled directory of vendors' legal data practices would rot silently, because policies change without any visible signal.

Settings paths are different. When a menu moves, it moves visibly, and anyone can check it in ten minutes per tool. That's why this list exists and the other one doesn't: staleness here is findable, and every page carries a date so you can see for yourself how fresh it is.

## Found something out of date?

Menus move. If a path here is wrong, [open a correction issue](https://github.com/VictorOsondu/ai-data-privacy-playbook/issues/new?template=correction.md) with the tool, the current path, and the date you checked. Corrections to this section get priority over everything else in the playbook.

---

*Practitioner guidance, not legal advice. Settings and defaults vary by product, plan, region, and account type — always confirm against your own account.*
