<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/qder-lockup-ltr-cobalt-white.svg">
    <img alt="Qder.ai" src="assets/qder-lockup-ltr-cobalt.svg" height="48">
  </picture>
</p>

**The AI waiter for restaurants in Israel.** A diner scans the code on the table and orders, asks about allergens
and pays from their own phone, in any language. The kitchen, the bar and the shift manager see every order the
moment it is sent.

[qder.ai](https://qder.ai) · [Status](https://status.qder.ai) · [LinkedIn](https://www.linkedin.com/company/qder) · [hello@qder.ai](mailto:hello@qder.ai)

<p align="center">
  <img src="assets/qder.gif" alt="Qder in use: a diner scans the table code, asks the waiter in their own language, gets suggestions checked against their allergies and orders in one tap; the order appears on the kitchen and bar screens and on the manager's live floor." width="680">
</p>

### What Qder does

| | |
|---|---|
| **At the table** | Scan the code, ask anything, in any language. Suggestions are checked against the allergies the diner mentioned, drinks with alcohol ask for an age check, and the order goes in with one tap. Pay and split from the same phone. |
| **In the kitchen and at the bar** | Each ticket lands on the right screen as it is sent, with its allergy notes and timing. |
| **On the floor** | The shift manager sees every table live: who is waiting, who called, what is late, bookings and the bill. |
| **Setting up** | Upload the menu; Qder reads it, finds the dishes and suggests their allergens for the venue to confirm. |

### Open source

Pieces of our stack that are useful on their own, maintained by the team that runs them in production.

| Repository | What it is |
|---|---|
| [hebrew-i18n](https://github.com/qderai/hebrew-i18n) | Translate a Hebrew-first site by its own text: one dictionary keyed by the Hebrew, applied in the browser and on the server alike, RTL-aware. |
| [icount-js](https://github.com/qderai/icount-js) | A typed client for the iCount invoicing API. |
| [israel-map-r2](https://github.com/qderai/israel-map-r2) | A self-hosted vector map of Israel: PMTiles on Cloudflare R2, served by a Worker, drawn with MapLibre. |
| [qder-brand](https://github.com/qderai/qder-brand) | Our logo, colours and how to use them. |
| [track-for-git](https://github.com/qderai/track-for-git) | A calm, real-time dashboard of a GitHub organisation: every commit, push and pull request, who made it and with which AI agent, what changed and what shipped. Self-hosted on Cloudflare Workers or Node. |

### Built with

TypeScript · Cloudflare Workers, D1 and R2 · React Native (diner app) · Flutter (staff screens)

<sub>Found a security issue? See our [security policy](https://github.com/qderai/.github/blob/main/SECURITY.md). © 2026 Qder AI.</sub>
