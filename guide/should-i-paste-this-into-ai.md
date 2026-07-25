# Should I Paste This Into AI?

Last reviewed: 2026-07-24. See [sources and verification notes](../sources.md).

Use this when you're about to paste, upload, dictate, screen-share, or connect data to an AI tool.

## First question: what tool am I using?

### Public or consumer AI tool

Use the strict rule:

> If you wouldn't publish it on a public website with your name attached, don't put it into a public AI tool.

This includes personal accounts, free chatbots, trial tools, browser extensions, unapproved plugins, and any product where you haven't checked the training, retention, deletion, memory, feedback, and human-review settings.

### Approved work tool

An approved work tool is not just "paid". It should be approved for the data type, covered by the right agreement, and configured by the organisation.

Before using it, check:

- Is this tool approved for this kind of data?
- Does the agreement say customer inputs and outputs are not used to train models by default?
- Are retention, deletion, admin, audit, access, and connected-app controls configured?
- Are file uploads, memory, voice, browser, screen, and third-party integrations allowed for this use?
- Does the task involve regulated, high-risk, or special-category data that needs extra review?

## What kind of data is it?

### Public information

Usually OK. Examples: public website copy, published documents, generic research questions, public product descriptions.

Still check for copyright, confidentiality, and whether the output will be used in a high-stakes context.

### Your own low-risk personal information

Usually OK with caution. Examples: a draft bio, a non-sensitive email, a travel plan.

Remove anything you don't need to share. Check memory and chat-history settings if you don't want the tool to reuse it later.

### Other people's personal data

Do not use a public AI tool. Use an approved work tool only if the data is needed for the task and your organisation permits that use.

Redact where possible:

- names
- addresses
- account numbers
- health details
- financial details
- employment details
- children's data
- anything that could identify the person

### Client, customer, or confidential work data

Do not use a public AI tool. Use an approved work tool only if the agreement, policy, and settings cover that data.

Prefer:

- summaries instead of raw records
- synthetic examples instead of real examples
- redacted documents instead of originals
- local or private workflows where sensitive data does not leave the approved environment

Local processing can reduce external data transfer, but confirm that the tool is approved and that sync, telemetry, updates, transcription, feedback, model routing, logs, and backups do not send or retain the data unexpectedly. A tool calling itself local isn't enough.

### Credentials and secrets

Never paste these into any AI tool:

- passwords
- API keys
- access tokens
- private keys
- recovery phrases
- database credentials
- session cookies

If a secret goes in, rotate or revoke it. Deleting the chat isn't enough.

### Regulated or high-risk data

Pause and get the right approval before using AI.

This includes:

- health, medical, therapy, or care information
- safeguarding information
- HR, hiring, disciplinary, or performance information
- financial, credit, insurance, or tax information
- legal advice or active disputes
- immigration, benefits, housing, or criminal justice information
- children's data
- special-category personal data under UK/EU data protection law

## Safer alternatives

- Ask a generic version of the question.
- Replace real data with placeholders.
- Use synthetic examples.
- Summarise the issue without names or identifiers.
- Use an approved enterprise tool with the right controls.
- Use an approved local workflow only after checking its model source, endpoint access, logs, sync, telemetry, backups, and deletion.
- Keep the task outside AI if the data cannot be shared safely.

## If the answer is unclear

Treat unclear as no for public tools. For work tools, treat unclear as "ask the owner" rather than guessing.
