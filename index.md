# ShipSwift Component MCP

ShipSwift Component MCP is a hosted remote MCP for ShipSwift.

This repository is a public documentation project for ShipSwift Component MCP. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://shipswiftcomponents.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=shipswiftcomponents_public_docs&utm_content=readme_home
- Pricing: https://shipswiftcomponents.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=shipswiftcomponents_public_docs&utm_content=readme_pricing
- Checkout: https://shipswiftcomponents.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=shipswiftcomponents_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://shipswiftcomponents.clauxel.com/mcp
- Server card: https://shipswiftcomponents.clauxel.com/server-card.json
- Registry name: `com.clauxel.shipswiftcomponents/shipswiftcomponents-mcp`
- Tools: `search_swiftui_component`, `generate_component_patch`, `validate_dependency_policy`, `export_component_receipt`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: search_swiftui_component
- MCP tool: generate_component_patch
- MCP tool: validate_dependency_policy
- MCP tool: export_component_receipt

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
