# What AI tools actually do with your data

Plain-English, no scaremongering. When you type something into an AI tool, several things *can* happen to it — depending on the tool, the tier, and the settings. Here's what to know, so you can decide what's safe to share.

## The five things that can happen to your input

1. **It's sent to a server.** Almost all AI chatbots run in the cloud. Your prompt leaves your device and is processed on the vendor's servers. (Local/on-device models are the exception — see the [checker extension](https://github.com/VictorOsondu/ai-data-practices-checker) note below.)
2. **It may be retained.** Many tools store your conversations — sometimes indefinitely, sometimes for a stated period. "Delete chat" in the interface doesn't always delete it from the vendor's systems.
3. **It may train future models.** On consumer/free tiers especially, your inputs can be used to improve the model. That means fragments of what you typed can influence outputs shown to other people.
4. **It may be reviewed by humans.** Vendors often allow staff or contractors to review a sample of conversations for quality and safety. Assume a human *could* read it.
5. **It may be shared with third parties or exposed in a breach.** Sub-processors, analytics, and plain old security breaches all apply to AI tools as much as any other service.

## The tier that changes everything

The single biggest variable is **free/consumer vs paid/enterprise**.

- **Consumer/free tiers** typically default to retention and training-on-your-data. Sometimes you can opt out in settings; often the default is "on".
- **Enterprise/business tiers** (with a proper agreement) usually commit *not* to train on your data, keep it in your tenant, and offer retention controls. This is why organisations that handle client or personal data must use enterprise tools for anything sensitive.

If you take one thing from this guide: **know which tier you're on, and check the training toggle.**

## What "training on your data" really means

It doesn't mean the model memorises your prompt word-for-word and reads it back to strangers (usually). It means your input becomes part of the statistical material the next model learns from. The risk is real but specific: sensitive, unique, or identifying content is the kind most likely to matter if it surfaced. Generic questions are low-risk; a paragraph of a confidential contract is not.

## The line: what never goes in

Regardless of tool or tier, treat these as never-goes-into-a-public-AI-tool:

- Other people's personal data (names + details, health, finances).
- Confidential work: contracts, unpublished data, client material, credentials, API keys.
- Anything you wouldn't be comfortable seeing on a public website.

**The test:** *Would I be comfortable if this input appeared publicly, attached to my name?* If not, don't paste it into a consumer tool — use an enterprise tool approved for that data, redact it, or don't use AI for that task.

## Checking a tool before you trust it

Privacy policies are long and evasive by design. Two shortcuts:

- Look specifically for the words **retention**, **training**, **human review**, and **opt-out**. Those four tell you most of what matters.
- Use the free, local-only **[AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker)** browser extension — it scans a privacy policy and quotes the clauses that describe AI-era data practices, so you don't have to read twenty pages. (It quotes what the policy says; it doesn't grade compliance — the judgement stays yours.)

Next: the [AI data-hygiene checklist](../checklist/ai-data-hygiene.md) and the [vendor red-flags list](../templates/vendor-red-flags.md).
