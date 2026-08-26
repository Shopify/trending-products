# Agent instructions

This repository is a prompt-first launch workflow for creating a Shopify trend store with a merchant.

## How to use this repo

- Start from `SKILL.md`.
- Use `prompts/launch-store.md` as the operating procedure and source of truth.
- Read `artifacts/README.md` to understand which working documents to create and maintain.
- Before starting or resuming work, inspect the existing files in `artifacts/` and continue from the first incomplete step.
- Keep artifacts merchant-readable. Update them as decisions are made instead of replacing prior context.
- Ask concise questions in batches and record the merchant's answers in the relevant artifact.
- Be explicit about assumptions, limitations, manual handoffs, account requirements, and costs.
- Stop for the approval gates defined in `prompts/launch-store.md`; do not treat a prior general preference as approval for a specific action.
- Do not purchase a domain, publish a theme, publish catalog items, connect a live domain, run paid generation, or send/activate marketing without explicit approval in the current conversation.

## Expected workflow files

- `prompts/launch-store.md` — full launch procedure.
- `artifacts/README.md` — artifact descriptions and expected contents.
- `artifacts/brand-brief.md` — merchant brief and brand decisions.
- `artifacts/research-brief.md` — research findings and approved opportunity direction.
- `artifacts/catalog-plan.md` — catalog, sourcing, pricing, and product confirmation plan.
- `artifacts/campaign-plan.md` — creative/image plan, asset status, and marketing approval state.
- `artifacts/launch-checklist.md` — store setup, QA, domain, launch blockers, owners, and approvals.

<!-- stripe-projects-cli managed:agents-md:start -->
## Stripe Projects CLI

This repository is initialized for the Stripe projects

## Tools used

- [Stripe CLI](https://docs.stripe.com/stripe-cli) with the `projects` plugin to manage third-party services, credentials, and deployments for this project. Use the stripe-projects-cli to manage deploying and access to third party services.
<!-- stripe-projects-cli managed:agents-md:end -->
