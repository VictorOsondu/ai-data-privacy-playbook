# Claude — where the privacy controls are

**Last verified: 2026-08-08** against [Anthropic's privacy documentation](https://privacy.claude.com/en/articles/10023548-how-do-you-use-personal-data-in-model-training) (vendor page dated 2026-07-01).

Claude is the odd one out, and in a good way. Where most consumer AI tools train on your chats unless you stop them, Claude's consumer plans don't unless you say yes.

## The setting

| | |
|---|---|
| **Name** | `Model Improvement` |
| **Path** | Settings → Data Privacy Controls |
| **Default** | **Opt-in.** Off unless you switch it on. |
| **Applies to** | Claude Free, Pro, and Max, including Claude Code used on those plans |
| **Doesn't apply to** | Claude for Work and the Anthropic API — commercial products are handled separately |

## What it does

Switch it **on** and Anthropic may use your conversations to train future models, retaining them in de-identified form for **up to five years**.

Switch it **off** — or leave it off — and your conversations aren't used for future model training.

Two details worth knowing:

- **Enabling it isn't retroactive.** It applies to new or resumed chats from the point you turn it on, not your whole history.
- **Disabling it isn't retroactive either.** Anything already inside a training run, or already baked into a released model, stays there. You can stop future use; you can't reach back.

**Incognito chats are never used to improve Claude**, even when Model Improvement is switched on.

## What people assume

> **"Every AI chatbot trains on my chats unless I stop it."**

Not here, on consumer plans. If you're methodically hardening your AI tools, this is the one where you should check the switch rather than assume you need to flip it. Flipping it *on* by mistake is the actual risk — and it comes with five-year retention attached.

> **"Turning it off deletes what they already have."**

It doesn't. Nothing about a training opt-out is retroactive at any vendor. If something sensitive went into a chat while the setting was on, treat it as shared: delete the conversation, and if credentials were involved, rotate them. Deletion and training are separate questions.

## Where to look next

- Retention rules for stored conversations sit in the same privacy centre and differ from the training question. Check both.
- Anthropic moved its privacy documentation from `privacy.anthropic.com` to `privacy.claude.com`. Old links still redirect, but if you've bookmarked or cited the old domain, update it.

---

Related: [what AI tools do with your data](../guide/what-ai-does-with-your-data.md) · [hygiene checklist](../checklist/ai-data-hygiene.md) · [all controls](README.md)
