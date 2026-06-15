# Onchain Suite Docs

Mintlify documentation source for `onchainsuite.com`.

## What This Repo Contains

- Operator docs for campaigns, intelligence, automation, settings, and integrations
- Developer docs for API authentication and future endpoint references
- Brand assets and product notes used to shape the documentation structure

## Local Development

Install the Mintlify CLI:

```bash
npm i -g mint
```

Run the docs locally from the repo root:

```bash
mint dev
```

The local preview typically runs at [http://localhost:3000](http://localhost:3000).

## Content Structure

- `index.mdx`: docs homepage
- `docs.json`: Mintlify site configuration
- `getting-started/`, `campaigns/`, `intelligence/`, `automation/`, `settings/`, `integrations/`, `api/`, `help/`: primary doc sections
- `logo/`: light and dark brand assets
- `internal-notes/`: tracked product source material, API references, and brand guidance kept outside Mintlify's markdown parsing path

## Publishing

Push changes to the connected Mintlify repo to publish updates through your Mintlify deployment workflow.
