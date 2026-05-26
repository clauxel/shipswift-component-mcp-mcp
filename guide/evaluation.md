# Evaluation Guide

Use this page to evaluate whether ShipSwift Component MCP fits a real workflow.

## What To Test

- ShipSwift
- ShipSwift Component MCP
- ShipSwift Component MCP documentation
- ShipSwift Component MCP remote MCP
- shipswiftcomponents server card

## Expected Evidence

- Open ShipSwift Component MCP and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://shipswiftcomponents.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call search_swiftui_component with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://shipswiftcomponents.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=shipswiftcomponents_public_docs&utm_content=evaluation_checkout
