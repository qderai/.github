<p align="left">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/qder-lockup-ltr-white.svg">
    <img alt="Qder.ai" src="assets/qder-lockup-ltr-cobalt.svg" height="44">
  </picture>
</p>

**The AI waiter for restaurants in Israel.** A diner scans the code on the table and orders, asks about allergens
and pays from their own phone, in any language. The restaurant runs its floor, kitchen and chain from Qder's panels
and screens.

[qder.ai](https://qder.ai) · [Status](https://status.qder.ai) · [LinkedIn](https://www.linkedin.com/company/qder) · [hello@qder.ai](mailto:hello@qder.ai)

### Open source

Pieces of our stack that are useful on their own, maintained by the team that runs them in production.

| Repository | What it is |
|---|---|
| [hebrew-i18n](https://github.com/qderai/hebrew-i18n) | Translate a Hebrew-first site by its own text: one dictionary keyed by the Hebrew, applied in the browser and on the server alike, RTL-aware. |
| [worker-status-page](https://github.com/qderai/worker-status-page) | A status page on a single Cloudflare Worker: scheduled probes, components, incidents and history, the page behind status.qder.ai. |
| [israeli-payments](https://github.com/qderai/israeli-payments) | One TypeScript interface over Israeli card processors (PayPlus, Hyp, Grow, Cardcom, Tranzila), with pinned payment pages and amounts in agorot. |
| [icount-js](https://github.com/qderai/icount-js) | A typed client for the iCount invoicing API. |
| [israel-map-r2](https://github.com/qderai/israel-map-r2) | A self-hosted vector map of Israel: PMTiles on Cloudflare R2, served by a Worker, drawn with MapLibre. |
| [qder-brand](https://github.com/qderai/qder-brand) | Our logo, colours and how to use them. |

### Built with

TypeScript · Cloudflare Workers, D1 and R2 · Flutter · our own AI model

<sub>Found a security issue? See our [security policy](https://github.com/qderai/.github/blob/main/SECURITY.md). © 2026 Qder AI.</sub>
