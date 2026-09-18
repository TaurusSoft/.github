# Contributing

Thanks for your interest in contributing to a TaurusSoft project!

## General workflow

1. Fork the repository and create a branch from `main`.
2. Make your changes, including tests where applicable.
3. Run `npm run lint` and `npm run build` locally before opening a PR — CI will run the same checks.
4. Open a pull request describing what changed and why.

## Commit messages

We use [Conventional Commits](https://www.conventionalcommits.org/) where possible (`fix:`, `feat:`, `chore:`, etc.).
This helps Renovate and any changelog tooling categorize changes automatically.

## Dependency updates

Dependency updates are managed automatically by [Renovate](https://github.com/renovatebot/renovate) — please don't
open manual PRs just to bump a version unless it's tied to a specific bug or feature.

## n8n node-specific guidelines

If you're contributing to an n8n community node:

- Follow the [n8n node development guidelines](https://docs.n8n.io/integrations/creating-nodes/)
- Run `eslint-plugin-n8n-nodes-base` checks (included in `npm run lint`)
- Test the node against a local n8n instance before submitting, especially for UI/property changes

## Code of Conduct

Be respectful and constructive. We want this to be a welcoming space for contributors of all experience levels.
