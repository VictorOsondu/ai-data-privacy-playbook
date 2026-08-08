# Google Gemini — where the privacy controls are

**Last verified: 2026-08-08** against the [Gemini Apps Privacy Hub](https://support.google.com/gemini/answer/13594961) (vendor page dated 2026-07-15).

## The setting

| | |
|---|---|
| **Name** | `Keep Activity` — previously called `Gemini Apps Activity`, and both names are still in circulation |
| **Path (web)** | [myactivity.google.com/product/gemini](https://myactivity.google.com/product/gemini), or gemini.google.com → Activity |
| **Path (mobile)** | Gemini app → profile picture → Gemini Apps Activity |
| **Default** | On for personal Google accounts |
| **Separate control** | Audio, Gemini Live video, and screen shares have their **own** setting |

Work and school Google accounts run under different terms. If you're using Gemini through Workspace, check the [Generative AI in Google Workspace Privacy Hub](https://support.google.com/a/answer/14186649) instead — the consumer settings above may not be the ones that govern you.

## What it does

With Keep Activity **on**, your Gemini conversations — including data from apps you've connected — can be used to improve Google's services, model training included.

With it **off**, in Google's own words: *"Your future chats won't appear in your Activity, and won't be used to train our AI models, unless you choose to send Google feedback."*

## What it doesn't do

Three things survive switching it off, and this is the part that catches people:

1. **Feedback re-opens the door.** Submitting feedback on a response — the thumbs up or down — puts that exchange back in scope for training, regardless of the setting.
2. **Chats are still retained for 72 hours.** Google keeps them briefly to deliver the service and support safety protections, then deletes them. "Off" means "not kept in your Activity and not trained on", not "gone the moment I close the tab".
3. **Human review is a separate track with a much longer clock.** Reviewers, including service providers, read a subset of conversations to assess quality and spot harmful content. Those reviewed chats are disconnected from your account and **kept for up to three years** — and that isn't undone by turning Keep Activity off.

## What people assume

> **"Turning off activity means nobody sees my chats."**

The single biggest gap between the label and the reality. A conversation already pulled for human review is disconnected from your account, but it persists for up to three years, and the off switch doesn't reach it. It's not a scandal — it's how quality and safety review works at most vendors — but nothing in the setting's name tells you.

> **"Deleting my activity un-trains the model."**

No. Deleting history removes it from your view and from future use. Anything already used in training stays used. This is true across every vendor in this section.

> **"One switch covers everything I do with Gemini."**

Audio, Gemini Live video, and screen sharing sit behind their own control. If you use voice or share your screen, checking Keep Activity alone leaves that stream governed by a setting you haven't looked at.

---

Related: [what AI tools do with your data](../guide/what-ai-does-with-your-data.md) · [hygiene checklist](../checklist/ai-data-hygiene.md) · [all controls](README.md)
