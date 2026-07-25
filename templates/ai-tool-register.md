# AI Tool Register

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

Use this register to track which AI tools are approved, for which data, and under which controls. If a tool is not listed here, treat it as unapproved for work data.

## Data Categories

- **Public** - already published or safe to publish.
- **Internal** - non-public business information that would be inconvenient but not harmful if exposed.
- **Confidential** - client, customer, proprietary, commercial, or sensitive business information.
- **Personal** - information about identifiable people.
- **Restricted** - health, safeguarding, children, HR cases, legal disputes, financial records, credentials, secrets, or regulated data.

## Register

| Tool | Owner | Account / plan | Deployment | Approved uses | Allowed data | Not allowed | Key controls checked | Review date | Status |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Example: ChatGPT Business | Operations | Business workspace | Cloud | Drafting, summarising, brainstorming | Public, Internal | Credentials, Restricted data unless separately approved | Training default, admin controls, retention, connected apps | YYYY-MM-DD | Example only |
|  |  |  |  |  |  |  |  |  |  |

## Tool Review Notes

For each tool, keep a short note or issue with answers to these questions:

- Does the vendor use prompts, outputs, files, or feedback for model training by default?
- Can training or model-improvement use be disabled?
- How long are prompts, outputs, uploaded files, feedback, metadata, and logs retained?
- What happens when a user deletes a chat or file?
- Can humans review prompts, outputs, files, feedback, or flagged content?
- Are sub-processors and third-party model providers named?
- Are connected apps, plugins, file access, browser access, voice, screen sharing, and agents enabled?
- Is deployment cloud, local, or hybrid? Can sync, telemetry, updates, transcription, feedback, or model routing send data elsewhere?
- For local tools, are model and installer provenance, endpoint permissions, local logs, backups, encryption, updates, and deletion understood?
- Is there a DPA, BAA, or equivalent agreement where needed?
- Are data residency, regional processing, or cross-border transfer terms clear?
- Are SSO, role management, audit logs, offboarding, admin defaults, and retention controls available?
- What data categories has the tool been approved for?
- Who owns the tool review and when is the next review due?

## Status Options

- **Approved** - may be used for the listed purposes and data categories.
- **Approved with limits** - may be used only under the listed restrictions.
- **Pilot** - testing only; no confidential, personal, restricted, client, or customer data.
- **Blocked** - must not be used for work.
- **Retired** - no longer used; access removed and data/export/deletion handled.

`Local` is a deployment mode, not an approval status. A local tool may reduce external data transfer while still creating risks through endpoint access, unverified models or installers, logs, backups, sync, telemetry, or insecure configuration.
