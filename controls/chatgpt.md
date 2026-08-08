# ChatGPT — where the privacy controls are

**Last verified: 2026-08-08**, in the live product on a **Plus** account. Anything not visible on that screen is listed as unconfirmed at the bottom rather than filled in from assumption.

## The setting

| | |
|---|---|
| **Name** | `Improve the model for everyone` |
| **Path** | Profile icon → Settings → Data controls |
| **State on a paid Plus account** | **On by default.** Verified 2026-08-08. |
| **Control type** | Not a one-tap toggle. The row shows the current state with a chevron and opens a sub-page. |
| **Does it stick?** | Yes. Set to `Off` on Plus and confirmed still off afterwards, 2026-08-08. |
| **Scope** | Account-wide, not per-device |

## What it does

With it on, OpenAI may use content you've shared with ChatGPT, including chats and saved memories, to help improve its models. Switch it off and new conversations aren't used for training.

It applies to your whole account, whichever device you're signed in on, so you only need to do it once. And like every other vendor here, it isn't retroactive: opting out covers what comes next, not what's already been used.

## What people assume

> **"I pay for it, so they're not training on my chats."**

Wrong, and this is the one worth checking today. On a **Plus** account, verified in the product, `Improve the model for everyone` was **On** by default. The consumer/paid distinction people rely on is really a consumer/**business** distinction: OpenAI documents business and API products as excluded from training by default, but a paid individual subscription is still a consumer product. Paying more gets you more usage, not a different data posture.

> **"I turned it off, because I saw it said On and tapped it."**

The row isn't a switch. It shows the current state and a chevron, and the actual control is on the page it opens. Tapping the row and backing out changes nothing. Go in, change it there, then come back and confirm the row now reads `Off` — that read-back is the only proof you actually changed something.

## The rest of the Data controls screen

Verified present on 2026-08-08. Names as they appear:

- `Improve the model for everyone`
- `Location`
- `Information shared with apps`
- `Shared links` — worth an occasional review, since shared links stay live until revoked
- `Archived chats`, `Archive all chats`
- `Delete all chats`

Accounts with ChatGPT Work features also show `Work network access` and `Reset ChatGPT Work`. If you don't have those features, expect a shorter list.

**Memory is not on this screen.** Whatever governs memory and personalisation lives in a different section of Settings, so checking Data controls alone leaves it unreviewed. Same story for Temporary Chat, which is a mode in the chat interface rather than a setting here.

## Still unconfirmed

Left blank on purpose until someone checks them:

- [ ] What the `Improve the model for everyone` sub-page actually contains, and whether it offers anything beyond a single on/off
- [ ] Where memory and personalisation controls live, and whether they're governed by this setting or a separate one
- [ ] What Temporary Chat retains, and for how long
- [ ] What deleting a conversation covers, and what it doesn't
- [ ] Whether the toggle appears at all on Team, Enterprise, and Edu plans. Business products are documented as excluded from training by default, but "excluded by default" and "the control is absent" are different things, and only one is verifiable by looking.

Free and Pro defaults are also unverified. This page records **Plus**, because that's the plan that was checked.

## One piece of context worth knowing

A US court order from May 2025, in the New York Times copyright case, required OpenAI to preserve output log data that would otherwise have been deleted. **That order was lifted**, with a later order taking effect from late September 2025, though data already retained under it and data tied to accounts flagged in the litigation are still held.

It matters because a lot of privacy advice written in mid-2025 says deletion in ChatGPT doesn't really delete, on account of that order. That advice is out of date. This comes from press coverage rather than the court record, so treat it as background rather than a citation.

---

Related: [what AI tools do with your data](../guide/what-ai-does-with-your-data.md) · [hygiene checklist](../checklist/ai-data-hygiene.md) · [all controls](README.md)
