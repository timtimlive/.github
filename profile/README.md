# TimTim.Live Open Source

### Build Live Events Into Anything.

Open-source developer tools powered by the TimTim.Live Global Event Distribution Network.

> **Developer Preview.** These tools work today and are still growing. Names and details may change before version 1.0.

**[See It Work](https://timtim.live/developers/demo)** · **[60-Second Quickstart](https://timtim.live/developers/quickstart)** · **[Developer Documentation](https://timtim.live/developers/docs)** · **[Try Sandbox](https://timtim.live/developers/sandbox)** · **[Explore Open Source](https://timtim.live/developers/open-source)**

## Pick your way in

| If you use… | Start here |
|---|---|
| **HTML** | Paste one line — no key, no install: `<script src="https://timtim.live/widget/events.js" data-city="Miami" data-category="music" async></script>` · [examples/html](https://github.com/timtimlive/timtim-live-events/tree/main/examples/html) |
| **JavaScript** | [`@timtim-live/events`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/events-js) — a small SDK for Node, browsers, Deno, Bun and edge · [`<timtim-events>`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/web-component) web component |
| **React** | [`@timtim-live/react`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/react) — `<TimTimEvents city="Miami" />` and `useTimTimEvents()` |
| **REST API** | [timtim-api-examples](https://github.com/timtimlive/timtim-api-examples) — plain `fetch` examples by goal: find, show, attribute, test-purchase, webhooks, cancellations, refunds |
| **WordPress** | [timtim-wordpress](https://github.com/timtimlive/timtim-wordpress) — the TimTim.Live Events plugin |
| **OpenAPI** | [timtim-openapi](https://github.com/timtimlive/timtim-openapi) — the OpenAPI 3.1 contract, JSON Schemas, examples and a Postman collection |

## Try it in one minute

No sign-up needed. This returns sample events (every name starts with "TEST EVENT — NO REAL MONEY"):

```bash
curl "https://api.timtim.live/v1/demo/events?city=Miami&category=music"
```

## TimTim.Live Developer Tools

Open-source tools for connecting websites, apps and platforms to TimTim.Live.

### What is open source

SDKs, widgets, adapters, examples and public API specifications.

### What is not included

This code shows events. It does not include TimTim.Live's own servers. Tickets, payments, payouts, fraud checks and everyone's private data stay with TimTim.Live. You reach them through the API.

These tools connect to the hosted TimTim.Live API at:

https://api.timtim.live

Open-source licenses for client software do not grant ownership of TimTim.Live event data, API services, commercial rights, certification marks or trademarks.

## Good to know

- **Sandbox first.** Test keys (`tt_test_…`) only ever see sample events. No real money moves. Get one at https://timtim.live/developers.
- **Security:** report problems privately with "Report a vulnerability" on a repository's Security tab. Policy: https://timtim.live/partners/security
- **Community:** https://timtim.live/developers/community
- **Status:** https://timtim.live/developers/status
- **Partners and business:** https://timtim.live/partners

Everything here is MIT licensed. Using the TimTim.Live API is covered by the [Partner Terms](https://timtim.live/partners/terms).
