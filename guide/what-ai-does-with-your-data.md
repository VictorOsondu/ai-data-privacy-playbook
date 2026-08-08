# What AI tools actually do with your data

Plain-English, no scaremongering. When you type something into an AI tool, several things *can* happen to it — depending on the vendor, product, account type, contract, settings, region, and feature. Here's what to know, so you can decide what's safe to share.

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

## The five things that can happen to your input

1. **It's sent to a server.** Almost all AI chatbots run in the cloud. Your prompt leaves your device and is processed on the vendor's servers. (Local/on-device models are the exception — see the [checker extension](https://github.com/VictorOsondu/ai-data-practices-checker) note below.)
2. **It may be retained.** Many tools store prompts, outputs, files, feedback, metadata, or safety logs for a stated period. Some keep certain records longer for security, abuse prevention, legal obligations, or product improvement. "Delete chat" in the interface doesn't always mean immediate deletion from every backend system.
3. **It may be used to improve models or services.** Some consumer products use chats for model training unless you opt out; others require opt-in. Business, enterprise, education, or API products often have different defaults. Always check the policy for the exact product you are using.
4. **It may be reviewed by humans.** Vendors may allow staff or contractors to review a sample of conversations, feedback, flagged content, or abuse/safety cases. Account settings can reduce some review, but they may not remove safety or legal review entirely.
5. **It may be shared with third parties or exposed in a breach.** Sub-processors, analytics, and plain old security breaches all apply to AI tools as much as any other service.

## The variables that change everything

The biggest visible variable is often **free/consumer vs paid/enterprise**, but it is not the only one.

- **Consumer/free tiers** may retain prompts and may use content to improve models or services, depending on the vendor and settings. Look for training controls, temporary chat modes, memory settings, feedback handling, and deletion windows.
- **Business/enterprise/API tiers** often commit not to train on customer inputs or outputs by default and may offer contractual controls, admin settings, audit logs, retention controls, access management, data residency, and DPAs. These controls are product-specific and should be checked before use.
- **Features can override your assumptions.** Connected apps, file uploads, browser or desktop agents, voice, screen sharing, memory, feedback buttons, plugins, and integrations may have separate data flows.

For where these controls actually sit in each tool, see **[Where the privacy controls actually live](../controls/README.md)** — click paths for Claude, Gemini, Copilot and ChatGPT, each dated with when it was last checked.

If you take one thing from this guide: **know the exact product and account you are using, then check the training, retention, memory, connected-app, and sharing controls.**

## What "training on your data" really means

It usually does not mean the model memorises your prompt word-for-word and reads it back to strangers. It means your input may become part of the data used to improve model behaviour, product quality, safety systems, or future model training. The risk is real but specific: sensitive, unique, or identifying content matters far more than generic questions. A public recipe prompt is low-risk; a paragraph of a confidential contract is not.

## The line: what never goes in

For public or consumer AI tools, treat these as never-goes-in:

- Other people's personal data (names + details, health, finances).
- Confidential work: contracts, unpublished data, client material, credentials, API keys.
- Anything you wouldn't be comfortable seeing on a public website.

**The public-tool test:** *Would I be comfortable if this input appeared publicly, attached to my name?* If not, don't paste it into a consumer tool. Use an approved work tool configured for that data, redact the input, use synthetic examples, or don't use AI for that task.

## What a DPA is, and when it becomes your problem

You'll see "DPA" in vendor documentation and in this playbook's checklists. It stands for **Data Processing Agreement**, and it's worth ninety seconds of your time because it decides more approvals than any privacy policy does.

Under UK and EU data protection law, whoever decides what personal data gets processed and why is the **controller**. Whoever processes it on their instruction is the **processor**. If you run a business, a charity, a school, or a practice, and you put other people's personal data into an AI tool, you're the controller and the vendor is the processor. The law expects a written contract between you, and that contract is the DPA. It covers what the vendor may do with the data, how long they keep it, who else they hand it to, and what happens when you leave.

Three things follow, and they're the useful part:

- **The accountability is yours.** Not the vendor's. "The tool didn't mention it" isn't a defence.
- **Free and consumer tiers generally don't offer a DPA.** This is usually the real reason a popular tool can't be approved for client or customer data, and it's a much faster conversation than arguing about privacy-policy wording.
- **An old DPA doesn't automatically cover new AI features.** Plenty of established suppliers have added AI to products you already use, under paperwork signed years earlier. Worth asking what changed.

If you're an individual using AI for your own work, with no one else's personal data involved, none of this applies to you. The moment client, patient, pupil, employee, or congregant data enters the picture, it does.

Not legal advice. Where children's data, health records, safeguarding information, or anything regulated is involved, get someone qualified to look rather than relying on a checklist.

## Checking a tool before you trust it

Privacy policies are long and often hard to compare. Two shortcuts:

- Look specifically for **retention**, **training**, **model improvement**, **human review**, **feedback**, **memory**, **connected apps**, **sub-processors**, **data residency**, **deletion**, and **opt-out**. Those terms tell you most of what matters.
- Use the free, local-only **[AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker)** browser extension — it scans a privacy policy and quotes the clauses that describe AI-era data practices, so you don't have to read twenty pages. (It quotes what the policy says; it doesn't grade compliance — the judgement stays yours.)

Next: the [AI data-hygiene checklist](../checklist/ai-data-hygiene.md) and the [vendor red-flags list](../templates/vendor-red-flags.md).
