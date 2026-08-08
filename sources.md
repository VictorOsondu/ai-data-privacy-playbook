# Sources and Verification Notes

Last reviewed: 2026-08-08.

The GitHub AI Adoption Playbook by GitHub is used and adapted with changes under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribution does not imply GitHub endorsement of this playbook.

This playbook uses primary vendor documentation, regulator guidance, and public standards where possible. Vendor policies change often, and the same vendor may apply different rules to consumer, business, enterprise, education, healthcare, API, beta, and connected-app features.

## How to read this

- Treat these links as verification starting points, not permanent guarantees.
- Check the exact product, account type, feature, region, and agreement before using AI with sensitive data.
- Prefer current vendor terms, data-processing agreements, trust portals, and admin documentation over marketing summaries.

## Vendor Data-Handling Sources

### OpenAI

- [How your data is used to improve model performance](https://openai.com/policies/how-your-data-is-used-to-improve-model-performance/) - states that individual services may use content to train models unless the user opts out, and that business/API products are opted out by default unless the organisation explicitly opts in.
- [Business data privacy, security, and compliance](https://openai.com/business-data/) - describes OpenAI's business-data commitments, training defaults for business products, encryption, retention controls, certifications, DPAs, and data residency options.

### Google Gemini

- [Gemini Apps Privacy Hub](https://support.google.com/gemini/answer/13594961?hl=en) - describes Gemini Apps data collection, activity settings, temporary chats, human review, retention, feedback handling, connected-app risks, and EU/UK legal-basis information.
- [Generative AI in Google Workspace Privacy Hub](https://support.google.com/a/answer/14186649?hl=en) - use this when checking Gemini features under work or school Google accounts, because Workspace data handling can differ from consumer Gemini Apps.

### Microsoft Copilot

- [Enterprise data protection in Microsoft 365 Copilot and Microsoft 365 Copilot Chat](https://learn.microsoft.com/en-us/microsoft-365/copilot/enterprise-data-protection) - describes enterprise data protection, service-boundary handling, subscription differences, and Microsoft's statement that prompts, responses, and Microsoft Graph data are not used to train foundation models.
- [Privacy and protections for Microsoft 365 Copilot Chat](https://learn.microsoft.com/en-ca/copilot/privacy-and-protections) - describes prompt processing, web grounding, logging, and protections for Copilot Chat.

### Anthropic Claude

- [How do you use personal data in model training?](https://privacy.claude.com/en/articles/10023548-how-do-you-use-personal-data-in-model-training) - the `Model Improvement` setting, its opt-in default on consumer plans, the five-year retention attached to enabling it, and the exclusion of Incognito chats. Vendor page dated 2026-07-01; checked 2026-08-08.
- [Data retention practices for Covered Models](https://privacy.claude.com/en/articles/15425996-data-retention-practices-for-covered-models) - specialised retention guidance for designated covered models.
- Note: Anthropic's privacy documentation moved from `privacy.anthropic.com` to `privacy.claude.com` and the old domain now 301-redirects. Links citing the old host still resolve, but should be updated when touched.

### Settings and controls (per-tool)

The [controls section](controls/README.md) documents where each vendor's training and retention settings live. Sources for those pages, with the date each was checked:

- [Microsoft Copilot privacy controls](https://support.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-privacy-controls) - names the consumer settings verbatim (`Training on conversation activity`, `Training on voice conversations`, `Personalization and memory`, `Microsoft usage data`), the click paths for web, mobile and the Edge sidebar, the uses opting out does *not* cover, and the regional rollout that explains a missing toggle. No last-updated date shown on the vendor page; checked 2026-08-08.
- [Gemini Apps Privacy Hub](https://support.google.com/gemini/answer/13594961) - the `Keep Activity` setting (renamed from `Gemini Apps Activity`), the 72-hour retention that applies when it's off, feedback as a route back into training, the separate audio/Live control, and human review retained up to three years. Vendor page dated 2026-07-15; checked 2026-08-08.
- **OpenAI — verification gap.** `help.openai.com` returns HTTP 403 to automated access, so the ChatGPT page could not be verified against the vendor's own documentation and is published with an unverified banner. Its setting name and path come from indexed copies of OpenAI help articles. Resolve by checking Settings → Data Controls in a live account and recording the plan tested.
- **Meta AI — not covered.** Its control is a regional objection form rather than a settings toggle, and the available accounts of it are secondary. Not written up until it can meet the same bar as the rest.

## Public Guidance and Frameworks

- [GitHub: Creating clear AI policies and guardrails](https://github.com/github/ai-adoption-playbook/blob/main/pillar_docs/policies_and_guardrails.md) - first-party practitioner guidance that distinguishes approved, public, and local tooling. This playbook adapts the deployment distinction while keeping approval status and data classification separate.
- [ICO: AI and data protection guidance](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/about-this-guidance/) - UK data protection guidance covering accountability, transparency, lawfulness, fairness, security, data minimisation, and rights in AI systems.
- [ICO: AI and data protection risk toolkit](https://ico.org.uk/for-organisations/uk-gdpr-guidance-and-resources/artificial-intelligence/guidance-on-ai-and-data-protection/ai-and-data-protection-risk-toolkit/) - practical toolkit for reducing risks to individuals' rights and freedoms.
- [NIST AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework) - voluntary framework for managing AI risks across governance, mapping, measurement, and management.
- [NIST AI Resource Center](https://airc.nist.gov/) - operational resources for applying the AI RMF.
- [European Commission: AI Act overview](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai) - official overview of EU AI Act obligations and implementation timeline. Use carefully because obligations phase in over time.

## Claims to Re-check Often

- Whether consumer chats are used for model training by default or only by opt-in.
- How temporary/private chats, memory, feedback, file uploads, voice, screen sharing, and connected apps are handled.
- Whether deletion removes data from history only, backend systems, safety logs, legal records, and training pipelines.
- Whether business, enterprise, API, education, and healthcare plans are excluded from model training by default.
- Whether DPAs, BAAs, data residency, audit logs, admin controls, SSO, and retention controls apply to the specific plan being used.
- Whether third-party model providers, plugins, extensions, or connected apps receive customer content.
- Whether the settings paths in the [controls section](controls/README.md) still match the live product. Menus move, and a stale click path is the fastest way for this playbook to lose trust.
