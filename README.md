# Copilot Connector Ledger MCP

Audit Copilot Studio connector permissions before agents inherit risky scopes.

Paid remote MCP for Copilot Studio connector permission audits, drift scans, owner signoff receipts, and compliance export packs.

## Public Endpoints

- Website: https://copilotconnectorledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://copilotconnectorledger.clauxel.com/mcp
- Server card: https://copilotconnectorledger.clauxel.com/server-card.json
- Registry name: `com.clauxel.copilotconnectorledger/copilotconnectorledger-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_connector_permission_risk`
- `scan_connector_drift`
- `request_owner_signoff`
- `generate_audit_pack`
- `export_connector_receipt`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://copilotconnectorledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://copilotconnectorledger.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://copilotconnectorledger.clauxel.com/server-card.json
- MCP endpoint: https://copilotconnectorledger.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
