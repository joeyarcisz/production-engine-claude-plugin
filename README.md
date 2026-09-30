# Production Engine for Claude

Production Engine is production management for commercial film and photo companies. This plugin connects Claude to your Production Engine workspace, so you can ask about your productions in plain language and get answers from your live data.

## What you can ask

- What's shooting and due this week, across every job?
- Is this job in trouble? What's blocking it?
- Who's called on the next shoot day, and where?
- Who still owes paperwork, and what do we owe crew?
- Are we over budget, and where?
- What's late, due soon or waiting on the client?
- Who owes us, and what do we owe?
- Where do our open bids stand?

With your approval, Claude can also price a new job from a plain description. It starts a draft estimate in Production Engine and gives you a link when it's ready.

## What's in the plugin

- **A connector** to Production Engine at `https://production-engine.com/api/mcp`.
- **A skill** that tells Claude which Production Engine tool answers which question.

The plugin runs no code on your computer.

## Getting connected

You need a Production Engine account, and you must be an owner or admin of the workspace on an active or trial plan. The first time Claude uses the plugin, Production Engine's sign-in page opens. Sign in, check the workspace, and click Allow. There is no token to copy. Pricing new jobs is a separate permission you can approve on the same screen.

Step-by-step setup for Claude and ChatGPT: https://production-engine.com/connect

## What it can read and change

Claude reads projects, budgets, actuals, purchase orders, invoices, vendors, contacts, schedules, crew, deliverables and bids, plus the bank feed and Saturation imports if your workspace has connected them. The only thing it can create is a draft estimate, and only if you approved pricing. Claude asks before it starts one. Everything else is changed in the Production Engine app.

## Data and privacy

The plugin sends requests only to production-engine.com. What Claude reads goes to Anthropic as part of your conversation. Production Engine records when each connection was last used. To disconnect, open Production Engine, go to Company Settings > Integrations, and disconnect Claude.

- Privacy policy: https://production-engine.com/privacy
- Support: intake@production-engine.com

## License

MIT. See [LICENSE](LICENSE).
