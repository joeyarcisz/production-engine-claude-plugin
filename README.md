<p align="center">
  <img src=".claude-plugin/icon.svg" width="72" height="72" alt="Production Engine">
</p>

<h1 align="center">Production Engine for Claude</h1>

<p align="center">
  Ask Claude about your productions and get answers from your live Production Engine workspace.<br>
  Call times, crew paperwork, budgets, deliverables, money and bids, in plain language.
</p>

<p align="center">
  <a href="https://production-engine.com">Website</a> ·
  <a href="https://production-engine.com/connect">Setup guide</a> ·
  <a href="https://production-engine.com/pricing">Pricing</a> ·
  <a href="https://production-engine.com/privacy">Privacy</a>
</p>

---

[Production Engine](https://production-engine.com) is production management for commercial film and photo companies: estimating on your own rate card, scheduling, call sheets, crew, budgets, invoicing and wrap, in one place. This plugin puts that workspace inside Claude, Claude Code and Cowork.

> **A Production Engine subscription is required.** The plugin is a secure connection to your own workspace. It holds no data and does nothing on its own. New companies can [start a free trial](https://production-engine.com/pricing) and connect in a few minutes.

## Ask Claude things like

| You ask | Claude answers from |
|---|---|
| "What's shooting and due this week?" | Every job's shoot days, deliverables, tasks, holds and permits |
| "Is the Northstar job in trouble?" | Risks, blockers and readiness for that job |
| "Who's called on Thursday, and where?" | The call sheet: call times, crew, locations and gear |
| "Who still owes paperwork?" | Start packets, deal memos and what you owe crew |
| "Are we over budget, and where?" | Budget vs. actuals, burn rate and forecast |
| "What's late or waiting on the client?" | Deliverables, due dates and review status |
| "Who owes us, and what do we owe?" | Receivables and payables by age, plus cash if your bank is connected |
| "Where do our open bids stand?" | The bid pipeline and forecast |

**Price a new job.** Describe a shoot and Claude starts a draft estimate in Production Engine, built on your own rates, then brings back the price paths and a link. This is a separate permission, and Claude asks before each estimate.

## How it works

- **Sign in, click Allow.** The first time Claude uses the plugin, Production Engine's sign-in page opens. There is no API key or token to copy.
- **Owners and admins only.** Only a workspace owner or admin can connect, and only on an active or trial plan. If a plan lapses, the connection stops working.
- **Read-only by default.** Claude reads your workspace. The only thing it can create is a draft estimate, and only if you approved pricing.
- **Nothing runs on your computer.** The plugin is a connector setting and a set of instructions for Claude. All work happens on production-engine.com.

## Install

**From the Claude directory:** search for **Production Engine** and click Connect. *(Listing in review.)*

**In Claude Code:**

```
/plugin marketplace add joeyarcisz/production-engine-claude-plugin
/plugin install production-engine@production-engine
```

**Claude.ai, desktop or mobile:** Settings > Connectors > Add custom connector, and paste `https://production-engine.com/api/mcp`.

Full steps for Claude and ChatGPT: [production-engine.com/connect](https://production-engine.com/connect)

## Data and privacy

- Requests go only to production-engine.com, over HTTPS.
- What Claude reads becomes part of your conversation with Claude, under Anthropic's terms.
- Production Engine records when each connection was last used. It does not store your conversations.
- Disconnect any time in Production Engine under **Company Settings > Integrations**.

[Privacy policy](https://production-engine.com/privacy) · [Terms](https://production-engine.com/terms)

## Support

Email [intake@production-engine.com](mailto:intake@production-engine.com) or visit [production-engine.com/connect](https://production-engine.com/connect).

---

© 2026 Geared Like A Machine LLC. Production Engine is a trademark of Geared Like A Machine LLC. See [LICENSE](LICENSE).
