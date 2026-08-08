# Changelog

This project follows [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Added
- **[controls/](controls/README.md)** — a per-tool map of where the training and retention settings actually live, with the click path, what each setting covers, and what it doesn't. Pages for [Claude](controls/claude.md), [Gemini](controls/gemini.md), [Copilot](controls/copilot.md) and [ChatGPT](controls/chatgpt.md), each carrying the date it was last checked.
- A verification table in the controls index, so staleness is visible rather than assumed.
- **What a DPA is, and when it becomes your problem** in [guide/what-ai-does-with-your-data.md](guide/what-ai-does-with-your-data.md) — plain-English controller/processor explanation, why free tiers generally offer no DPA, why an old DPA may not cover newly added AI features, and the line where it stops applying to individuals. The acronym already appeared in three checklists with nothing explaining it.

### Changed
- Cross-linked the controls section from the README, the hygiene checklist's training-control item, and the settings paragraph in *What AI tools actually do with your data*.
- Updated the Anthropic source to the model-training article and noted the `privacy.anthropic.com` → `privacy.claude.com` domain move. Removed the superseded "Updates to our Privacy Policy" link, which no longer added anything the other two didn't cover.

### Known gaps
- **[controls/chatgpt.md](controls/chatgpt.md) is partially verified.** The Data controls screen was checked in-product on a Plus account (2026-08-08), confirming `Improve the model for everyone` is **on by default on a paid plan** and that the row opens a sub-page rather than acting as a toggle. Still open: the sub-page contents, where memory lives, Temporary Chat retention, deletion coverage, and Free/Pro/Team/Enterprise/Edu defaults. Listed on the page as an explicit checklist rather than guessed at.
- **Meta AI is not covered.** Its control is a regional objection form and the available accounts of it are secondary. Deferred rather than written up thinly.

- Cross-linked **[AI Prompt Injection, Explained](https://github.com/VictorOsondu/ai-prompt-injection-explained)** from the series section and from the connected-apps item in the hygiene checklist. That explainer covers the security side — what someone else can make your assistant do — which this playbook doesn't.

## [0.1.0] — 2026-07-24

### Added
- Lean launch of the AI-Era Data & Privacy Playbook (Track C).
- **[guide/what-ai-does-with-your-data.md](guide/what-ai-does-with-your-data.md)** — what happens to your input, and the product/account/settings distinctions that change the risk.
- **[guide/should-i-paste-this-into-ai.md](guide/should-i-paste-this-into-ai.md)** — decision tree for what can safely go into AI tools.
- **[checklist/ai-data-hygiene.md](checklist/ai-data-hygiene.md)** — a personal AI data-hygiene checklist.
- **[templates/vendor-red-flags.md](templates/vendor-red-flags.md)** — red/green flags for judging a tool's data practices, mirroring the AI Data-Practices Checker extension.
- **[templates/small-team-ai-data-policy.md](templates/small-team-ai-data-policy.md)** — starter data policy for small teams.
- **[templates/ai-tool-register.md](templates/ai-tool-register.md)** — lightweight AI tool approval register.
- **[sources.md](sources.md)** — primary sources and verification notes.
- **[SECURITY.md](SECURITY.md)** and issue templates for safer public maintenance.
- Added cloud, local, and hybrid deployment mode to the tool register.
- Added guidance that local processing may reduce external transfer but is not automatically approved or safe.

### Notes
- `practitioner-built`, companion to the shipped [ai-data-practices-checker](https://github.com/VictorOsondu/ai-data-practices-checker) extension.
