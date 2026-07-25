# Small-Team AI Data Policy

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

Use this as a starter policy for a small team. Adapt it to your tools, contracts, jurisdiction, and risk level. This is not legal advice.

## Purpose

We use AI tools to work faster and improve quality, but we do not trade away client trust, personal privacy, or security for convenience.

This policy sets simple rules for what data can and cannot be used with AI tools.

## Scope

This policy applies to:

- employees
- contractors
- volunteers
- freelancers
- anyone using AI tools for work on our behalf

It covers:

- chatbots
- copilots
- writing tools
- image, audio, and video tools
- browser extensions
- AI meeting tools
- plugins and connected apps
- API-based AI tools
- automations and agents

## Core Rules

1. Do not put confidential, client, customer, employee, or personal data into a public AI tool.
2. Use only approved tools for work data.
3. Do not paste credentials, API keys, passwords, tokens, private keys, or recovery phrases into any AI tool.
4. Redact or anonymise data before using AI unless the approved tool is explicitly cleared for the original data.
5. Do not connect AI tools to email, drives, calendars, browsers, CRMs, finance tools, or messaging accounts unless approved.
6. Check outputs before using them. AI can be wrong, incomplete, biased, or misleading.
7. Report accidental data sharing quickly. Do not hide it.

## Data Categories

### Public data

Examples: published website copy, public reports, public policies, generic prompts.

Allowed in approved or public tools, subject to copyright and quality review.

### Internal data

Examples: internal notes, draft plans, non-public process documents.

Allowed only in approved work tools unless the information is harmless if made public.

### Confidential or client data

Examples: contracts, client files, customer records, unpublished strategy, proprietary data.

Allowed only in approved work tools that are cleared for this data type. Prefer redaction or summaries.

### Personal data

Examples: names plus details, contact records, customer messages, staff records.

Allowed only where there is a clear work need, an approved tool, and appropriate data-protection handling.

### Restricted data

Examples: health, safeguarding, children's data, HR cases, legal disputes, financial records, credentials, secrets.

Do not use with AI unless explicitly approved for that exact use case.

## Approved Tools

We keep an [AI tool register](ai-tool-register.md) showing:

- approved tools
- approved use cases
- data categories allowed
- account type or plan
- owner
- review date
- key restrictions

If a tool is not on the register, treat it as unapproved for work data.

## Minimum Vendor Checks

Before approving a tool, check:

- whether inputs and outputs are used for model training
- retention and deletion rules
- human-review rules
- sub-processors and third-party model providers
- connected-app, plugin, file, voice, and screen-sharing behaviour
- DPA or equivalent contract terms
- data residency where relevant
- admin controls, SSO, audit logs, offboarding, and retention settings
- breach notification
- security certifications or trust documentation

Use the [AI vendor privacy red-flags](vendor-red-flags.md) checklist.

## Incident Response

If data goes into the wrong AI tool:

1. Delete the conversation or uploaded file where possible.
2. If credentials or secrets were exposed, rotate or revoke them immediately.
3. Tell the relevant owner or manager.
4. Record what was shared, when, with which tool, and what action was taken.
5. If personal data was involved, involve the person responsible for data protection.

## Review

Review this policy at least every six months, and sooner when:

- a major AI tool changes its terms
- a new connected-app or agent feature is enabled
- a new category of data is proposed for AI use
- an incident or near miss happens
