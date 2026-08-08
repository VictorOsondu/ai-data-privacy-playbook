# AI-Era Data & Privacy Playbook

![Last updated](https://img.shields.io/badge/last%20updated-2026--08--08-00d4aa)
![Track](https://img.shields.io/badge/track-topic%20playbook-1a1a2e)
![Practitioner-built](https://img.shields.io/badge/practitioner--built-yes-f0a500)
![Licence](https://img.shields.io/badge/licence-CC%20BY%204.0-00d4aa)

A plain-English playbook for protecting your data in the age of AI — for individuals and small teams. Not scaremongering, and not "delete everything and hide". Just a clear account of what AI tools can do with what you type, and the handful of habits that reduce avoidable risk.

It's the companion to the free, local-only **[AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker)** browser extension: the extension scans a privacy policy and quotes the AI-era clauses; this playbook tells you what to do about them.

## Contents

- [Who this is for](#who-this-is-for)
- [The one idea](#the-one-idea)
- [What's inside](#whats-inside)
- [Start here](#start-here)
- [Where this came from](#where-this-came-from)
- [Free vs done-with-you](#free-vs-done-with-you)
- [Part of a series](#part-of-a-series)

## Who this is for

- **Individuals** who use ChatGPT, Copilot, Gemini and the rest, and want to know what's safe to type.
- **Small teams and solo operators** handling client or customer data without a privacy department.
- **Anyone vetting an AI tool** before trusting it with something that matters.

## The one idea

Most everyday AI data risk reduces to one habit:

> **Know your tier, check your toggles, and never paste what you wouldn't publish.**

For public or consumer AI tools, the safest default is to treat prompts as if they could be retained, reviewed, or reused unless the vendor clearly says otherwise. For work, the bigger question is whether the tool is approved for that data, covered by the right agreement, and configured correctly. Product tier matters, but so do vendor policy, account type, admin controls, connected apps, settings, region, and the specific feature you are using.

## What's inside

- 📖 **[What AI tools actually do with your data](guide/what-ai-does-with-your-data.md)** — the five things that can happen to your input, and the settings that change the risk.
- ✅ **[Personal AI data-hygiene checklist](checklist/ai-data-hygiene.md)** — setup, the before-every-prompt habit, and what to do if something went in that shouldn't have.
- 🎛️ **[Where the privacy controls actually live](controls/README.md)** — per-tool click paths for the training and retention settings in Claude, Gemini, Copilot and ChatGPT, with what each setting does *and* what it quietly doesn't. Every page is dated.
- 🧭 **[Should I paste this into AI?](guide/should-i-paste-this-into-ai.md)** — a decision tree for public tools, approved work tools, personal data, client data, credentials, and regulated data.
- 🚩 **[AI vendor privacy red-flags](templates/vendor-red-flags.md)** — how to judge a tool's data practices before you trust it.
- 📋 **[Small-team AI data policy](templates/small-team-ai-data-policy.md)** and **[AI tool register](templates/ai-tool-register.md)** — lightweight templates for teams without a privacy department.
- 🔎 **[Sources and verification notes](sources.md)** — primary sources used to keep this playbook current.

## Start here

1. Read **[What AI tools do with your data](guide/what-ai-does-with-your-data.md)** — ten minutes, and the point about tiers and settings alone is worth it.
2. Use **[Should I paste this into AI?](guide/should-i-paste-this-into-ai.md)** before sharing anything sensitive.
3. Run the **[hygiene checklist](checklist/ai-data-hygiene.md)** on your own setup, using **[the controls pages](controls/README.md)** to find each toggle.
4. Before trusting a new tool, run its policy through the **[checker extension](https://github.com/VictorOsondu/ai-data-practices-checker)** and the **[red-flags list](templates/vendor-red-flags.md)**.

## Where this came from

This playbook is built on the same work as the shipped **[AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker)** extension — a real, local-only tool that scans privacy policies for AI-era data practices — and on AI Tutorium's safe-use training. Its claims are grounded in vendor documentation and public guidance listed in [sources.md](sources.md); it doesn't promise privacy guarantees it can't keep.

## Free vs done-with-you

The playbook, checklist, and red-flags list are free to use and adapt under CC BY 4.0. Data-practice reviews and staff training for organisations are the paid work [AI Tutorium](https://aitutorium.com) does.

## Part of a series

A topic playbook alongside the **[AI Adoption Playbooks](https://github.com/VictorOsondu/ai-adoption-playbooks)** series and **[AI Prompt Injection, Explained](https://github.com/VictorOsondu/ai-prompt-injection-explained)** — this playbook is about what a vendor does with the data you hand over, that one is about what a stranger can make your assistant do with text it was only asked to read.

## Scope

This is practical public guidance for individuals and small teams. It is UK/EU-aware, but it is not a jurisdiction-specific compliance manual. Vendor policies change often; check the linked sources and the vendor's current terms before relying on any tool for sensitive, client, employee, health, financial, safeguarding, or regulated data.

---

> *"The more the world runs on data, the more it needs people who run on care."*

Maintained by [Victor Osondu](https://aitutorium.com), Founder, AI Tutorium. Corrections and translations welcome — see [CONTRIBUTING.md](CONTRIBUTING.md).

*This playbook is practitioner guidance, not legal advice. For regulated processing, involve your DPO or qualified counsel.*
