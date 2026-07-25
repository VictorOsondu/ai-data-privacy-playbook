# AI Vendor Privacy Red-Flags

A checklist for judging an AI tool's data practices before you trust it with anything that matters. Mirrors what the [AI Data-Practices Checker](https://github.com/VictorOsondu/ai-data-practices-checker) extension scans a privacy policy for. Green means reassuring; red means slow down.

Read the vendor's privacy policy and terms with these in mind. If you can't find an answer, treat the silence as amber — vague is not the same as safe.

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

## 🔴 Red flags — be cautious

- **Trains on your data by default with no opt-out**, or the opt-out is buried or only on paid tiers.
- **Indefinite or unstated retention** — no mention of how long inputs are kept.
- **Unclear deletion behaviour** — no distinction between deleting chat history, backend deletion, safety logs, legal holds, feedback retention, and training pipelines.
- **No mention of human review**, or broad rights for staff/contractors to read prompts, files, feedback, flagged content, or connected-app data.
- **Vague third-party sharing** — "we may share with partners" with no specifics.
- **Unclear model or provider routing** — the tool may send data to external model providers without naming them.
- **No data-residency information** — you can't tell where your data is processed (matters for UK/EU GDPR).
- **No enterprise/business tier** with a real data-processing agreement, if you handle client or personal data.
- **Silence on breach notification** — no commitment to tell you if something goes wrong.
- **Ownership grab** — terms claiming broad rights over your inputs or outputs beyond what's needed to run the service.
- **Connected-app sprawl** — broad access to email, drives, calendars, browsers, screens, voice, or desktop actions without clear controls.
- **No admin controls** for teams — no role management, SSO, audit logs, data export, or user offboarding.
- **No clear subprocessors list** or no process for updates to that list.

## 🟢 Green flags — reassuring

- **Clear "we don't train on your data" commitment**, at least on the business tier, ideally by default.
- **Stated, bounded retention** with a way to delete, plus clear exceptions for safety, security, legal, feedback, and abuse-prevention records.
- **Enterprise tier with a DPA** and appropriate contractual, access, retention, and isolation controls for business customers.
- **Named sub-processors** listed publicly and kept up to date.
- **Data-residency options** (e.g. UK/EU processing).
- **Clear controls** for training, history, memory, feedback, connected apps, file access, and temporary/private chats.
- **Admin controls** such as SSO, role-based access, audit logs, user offboarding, retention controls, and workspace-level settings.
- **Certifications** (SOC 2, ISO 27001) — not proof of good privacy, but a signal of seriousness.
- **Plain-language policy** — a vendor that explains itself clearly usually has less to hide.

## How to use this

1. For a **personal tool**, a couple of reds is a reason to keep sensitive content out — not necessarily to avoid the tool for casual use.
2. For a **work/organisation tool**, reds on retention, training, or residency should block use for anything above public data until resolved.
3. When in doubt, run the policy through the [checker extension](https://github.com/VictorOsondu/ai-data-practices-checker) — it quotes the exact clauses so you're judging the vendor's own words, not a marketing summary.

*This helps you ask better questions of a vendor. It isn't a compliance certification or legal advice — for regulated processing, involve your DPO.*
