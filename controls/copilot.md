# Microsoft Copilot — where the privacy controls are

**Last verified: 2026-08-08** against [Microsoft Copilot privacy controls](https://support.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-privacy-controls) (no last-updated date shown on the vendor page).

This page covers **consumer Copilot** — copilot.com, the mobile app, and the Edge sidebar. Microsoft 365 Copilot at work is a different product with different commitments; see the note at the bottom.

Copilot has the most confusing layout of any tool here, because the settings people need are split across **two separate menus**.

## The settings

### Training — in the Privacy menu

| | |
|---|---|
| **Names** | `Training on conversation activity` and `Training on voice conversations` |
| **Path (web)** | Profile icon → profile name → Privacy |
| **Path (mobile)** | Menu → profile icon → Account → Privacy |
| **Path (Edge sidebar)** | Sidebar menu (⋯) → Settings → Privacy |

### Memory — in a different menu entirely

| | |
|---|---|
| **Names** | `Personalization and memory` and `Microsoft usage data` |
| **Path (web)** | Profile icon → profile name → Memory |
| **Path (mobile)** | Menu → profile icon → Memory |
| **Path (Edge sidebar)** | Sidebar menu (⋯) → Settings → Memory |

## What opting out does

Switching off `Training on conversation activity` excludes your future conversations from AI model training. Voice is a separate toggle, so if you talk to Copilot, you need both.

## What it doesn't do

Opting out of training does **not** stop your data being used for:

- general product and system improvement
- advertising
- digital safety
- security
- compliance

Those uses are governed by the Microsoft Privacy Statement, not by the training toggle. There's a separate `See ads that interest you` control for personalised advertising.

## What people assume

> **"I turned off personalisation, so it's not training on me."**

The most common and most costly mistake with Copilot. `Personalization and memory` and `Training on conversation activity` are independent settings in different menus. You can switch off memory and still be training the model; you can also opt out of training and **keep** personalisation, so Copilot still remembers your recent conversations while Microsoft doesn't use them for training. If you only visited one menu, you've configured half of what you think you did.

> **"The toggle is missing, so my opt-out is broken."**

Not necessarily. Microsoft is rolling training and its opt-out controls out gradually, and in some countries conversation history isn't used for model training at all. Where that's the case, the setting doesn't appear — because there's nothing to opt out of. A missing toggle can mean you're already excluded. Worth confirming for your own region rather than guessing either way.

> **"Opting out means Microsoft stops using my data."**

It means they stop using it *for model training*. The list above still applies. This is a narrower promise than the toggle's name suggests, and it's stated plainly in Microsoft's own documentation.

## If you use Copilot at work

Microsoft 365 Copilot and Copilot Chat under a work tenant are covered by enterprise data protection, and Microsoft states that prompts, responses, and Microsoft Graph data aren't used to train the foundation models. Different product, different commitments, different admin controls — don't reason from your personal account to your work one, or the reverse.

---

Related: [what AI tools do with your data](../guide/what-ai-does-with-your-data.md) · [hygiene checklist](../checklist/ai-data-hygiene.md) · [all controls](README.md)
