# Modem Documentation

Product documentation for [Modem](https://modem.dev) — the developer-focused CRM that helps teams understand user feedback.

## Structure

```
docs/
├── index.mdx                    # Introduction
├── quickstart.mdx               # Getting started guide
├── core-concepts.mdx            # Key concepts explained
├── use-cases.mdx                # Real-world examples
├── guides/                      # Understanding your data
│   ├── topics.mdx
│   ├── participants.mdx
│   └── feedback-categories.mdx
├── integrations/                # Data source setup
│   ├── overview.mdx
│   ├── slack.mdx
│   ├── discord.mdx
│   ├── github.mdx
│   ├── linear.mdx
│   ├── email.mdx
│   └── mcp.mdx
└── features/                    # Feature documentation
    ├── ai-analysis.mdx
    ├── technical-crm.mdx
    ├── agent.mdx
    ├── scheduled-tasks.mdx
    ├── team-management.mdx
    └── security-privacy.mdx
```

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview documentation changes locally:

```bash
npm i -g mint
```

Run the development server:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing

Changes pushed to the `main` branch are automatically deployed via the Mintlify GitHub app.

## Resources

- [Mintlify documentation](https://mintlify.com/docs)
- [Modem dashboard](https://app.modem.dev)
