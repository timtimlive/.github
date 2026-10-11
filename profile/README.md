# TimTim.Live Open Source

### Build Live Events Into Anything.

Open-source developer tools powered by the TimTim.Live Global Event Distribution Network.

> **Developer Preview.** These tools work today and are still growing. Names and details may change before version 1.0.

**[Choose How to Connect](https://timtim.live/developers/connect)** · **[See It Work](https://timtim.live/developers/demo)** · **[Make Your Embed](https://timtim.live/developers/widget)** · **[60-Second Quickstart](https://timtim.live/developers/quickstart)** · **[Developer Documentation](https://timtim.live/developers/docs)** · **[Try Sandbox](https://timtim.live/developers/sandbox)**

Not sure where to start? **[timtim.live/developers/connect](https://timtim.live/developers/connect)** asks one question — *where do you want events to show?* — and gives you one button that works today.

## Pick your way in

**"Works today"** means you can use it right now. **"Not listed yet"** means the code works from GitHub but is not in that platform's store or package registry yet.

### I have a website

| If you use… | Start here | Status |
|---|---|---|
| **Any website (HTML)** | Paste two lines — no key, no install. Make them at [timtim.live/developers/widget](https://timtim.live/developers/widget):<br>`<script src="https://timtim.live/embed/v1/timtim-events.js" defer></script>`<br>`<timtim-events location="Miami,US" category="music"></timtim-events>` | Works today |
| **WordPress** | [timtim-wordpress](https://github.com/timtimlive/timtim-wordpress) — a block and a shortcode | Works today (download from timtim.live) |
| **Shopify · Wix · Webflow · Squarespace · Bubble** | Paste the same two lines into the platform's code box. Steps for each: [platforms/](https://github.com/timtimlive/timtim-live-events/tree/main/platforms) | Works today. Store apps not listed yet |
| **Framer** | [A code component](https://github.com/timtimlive/timtim-live-events/tree/main/platforms/framer) with every setting in the side panel | Works today |
| **Drupal · Joomla** | Install the [Drupal module](https://github.com/timtimlive/timtim-live-events/tree/main/platforms/drupal) or the [Joomla module](https://github.com/timtimlive/timtim-live-events/tree/main/platforms/joomla) | Works today. Directories not listed yet |

### I write code

| If you use… | Start here | Status |
|---|---|---|
| **JavaScript** | [`@timtim-live/events`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/events-js) — a small SDK for Node, browsers, Deno, Bun and edge · [`<timtim-events>`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/web-component) web component | Works from GitHub. Not on npm yet |
| **React / Next.js** | [`@timtim-live/react`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/react) — `<TimTimEvents city="Miami" />` and `useTimTimEvents()` | Works from GitHub. Not on npm yet |
| **REST API, any language** | [timtim-api-examples](https://github.com/timtimlive/timtim-api-examples) — plain `fetch` examples by goal: find events, show them, events near a hotel, music this weekend, things to do nearby, test purchases, webhooks | Works today |
| **OpenAPI · Postman** | [timtim-openapi](https://github.com/timtimlive/timtim-openapi) — the OpenAPI 3.1 contract, JSON Schemas, examples and a ready-made Postman collection | Works today |

### I build a mobile app

| If you use… | Start here | Status |
|---|---|---|
| **React Native / Expo** | [`@timtim-live/react-native`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/react-native) — a ready-made event list | Works from GitHub. Not on npm yet |
| **iPhone (Swift)** | [mobile/ios](https://github.com/timtimlive/timtim-live-events/tree/main/mobile/ios) — a Swift package | Works from GitHub |
| **Android (Kotlin)** | [mobile/android](https://github.com/timtimlive/timtim-live-events/tree/main/mobile/android) — a Kotlin client | Works from GitHub |

### I use an AI assistant

| If you use… | Start here | Status |
|---|---|---|
| **Claude, Cursor, VS Code or another MCP app** | Paste one address: `https://api.timtim.live/v1/mcp` — steps at [timtim.live/developers/ai](https://timtim.live/developers/ai). Or run [`@timtim-live/mcp`](https://github.com/timtimlive/timtim-live-events/tree/main/packages/mcp) yourself | Works today |

### I use a calendar or newsletter

| If you use… | Start here | Status |
|---|---|---|
| **Google / Apple / Outlook calendar, RSS, spreadsheets** | Subscribe to a feed (ICS, RSS, JSON, XML or CSV) with your free test key or website key — addresses at [timtim.live/partners/docs#feeds](https://timtim.live/partners/docs#feeds) | Works today |

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
