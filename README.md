# Shopify Trend Store Launchpad

This is a prompt-first Stripe Projects template for new Shopify merchants. It provisions the connected research, commerce, creative, and domain services, then gives your coding agent a structured launch workflow.

Start with your preferred coding agent:

```sh
codex "Launch my Shopify trend store. Follow SKILL.md."
```

The agent will work with you to research a product opportunity, define the brand, create a store plan, produce marketing assets, and help prepare a new Shopify store.

## What the template provisions

- Shopify store
- Firecrawl API for trend and competitor research
- OpenRouter API for photo cleanup and restyling
- Spaceship domain search and purchase flow

## Outputs

The launch workflow creates and maintains these merchant-owned working documents in `artifacts/`:

- `research-brief.md`
- `brand-brief.md`
- `catalog-plan.md`
- `campaign-plan.md`
- `launch-checklist.md`

## Shopify CLI boundary

Shopify CLI is used for theme, app, and Hydrogen development, plus theme push/publish. Store creation and catalog administration require the authorized Shopify store workflow or Admin API; the prompt never represents Shopify CLI as a substitute for those permissions.
