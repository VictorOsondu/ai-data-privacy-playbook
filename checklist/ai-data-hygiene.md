# Personal AI Data-Hygiene Checklist

A practical checklist for using AI tools without leaking things you'll regret. Works for individuals and as a starter for a small team. Tick what's true; act on what isn't.

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

## Setup (do once)

- [ ] I know which **tier** I'm on for each AI tool I use (free/consumer vs paid/enterprise).
- [ ] I've checked the **training / model-improvement control** and turned off data sharing where I don't want it.
- [ ] I've checked the **chat history / retention** setting and set it to what I actually want.
- [ ] I've checked **memory / personalisation** settings and cleared anything I don't want reused later.
- [ ] I've checked **connected apps, plugins, browser extensions, file access, voice, and screen-sharing** settings. Connectors are also how a hidden instruction in a document reaches your accounts — the [personal AI security checklist](https://github.com/VictorOsondu/ai-prompt-injection-explained/blob/main/checklist/personal-ai-security.md) goes through permissions and prompt injection in detail.
- [ ] For work, I use an **approved/enterprise** tool for anything touching client or personal data — not a personal account.

## Before every prompt (the habit)

- [ ] I've asked: *would I be comfortable if this input appeared publicly, next to my name?* If no, it doesn't go in.
- [ ] I've removed or **redacted** names and identifying details I don't need to include.
- [ ] No **credentials, API keys, passwords, or financial details** are in the prompt.
- [ ] No private files, emails, calendar data, customer records, or screenshots are attached unless the tool is approved for that data.
- [ ] If it's confidential work, I'm using an **approved tool**, not a free chatbot.

## What never goes in (memorise this)

- [ ] Other people's personal data (names + details, health, finances, anything sensitive).
- [ ] Confidential or unpublished work — contracts, client material, unreleased data.
- [ ] Safeguarding, HR, medical, or pastoral information about a real person.
- [ ] Credentials, secrets, authentication tokens, private keys, or recovery phrases.
- [ ] Anything I wouldn't publish on a public website.

## Periodic (every few months)

- [ ] I've cleared old conversations I don't need retained.
- [ ] I've re-checked settings after major tool updates, new features, or plan changes.
- [ ] I've reviewed which AI tools have access to my accounts (Google/Microsoft integrations, browser extensions) and removed ones I don't use.
- [ ] I've run a privacy-policy check on any new tool before trusting it — the [AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker) makes this a two-minute job.

## If something went in that shouldn't have

- [ ] I've deleted the conversation (knowing this may not remove it from the vendor's systems).
- [ ] If credentials, API keys, tokens, or recovery phrases were exposed, I've rotated or revoked them rather than relying on deletion.
- [ ] For work data, I've reported it through the right channel so it's handled, not hidden.
- [ ] If personal data of others was involved, I've flagged it to whoever owns data protection — a near-miss handled openly is far better than one covered up.

---

> **The one rule that covers most of this:** know your tier, check your toggles, and never paste what you wouldn't publish. Everything else is refinement.
