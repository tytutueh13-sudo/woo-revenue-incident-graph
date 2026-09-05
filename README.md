# Woo Revenue Incident Graph

Woo Revenue Incident Graph is a portable Agent Plugin for a hosted, read-only
MCP server. It helps investigate whether a WooCommerce checkout or revenue
change lines up with a plugin, theme, WooCommerce core, gateway, or checkout
surface change.

## What the remote MCP provides

- A privacy-safe checkout health snapshot.
- A bounded revenue-incident diagnosis.
- A pre-change checkout risk check.
- A post-change revenue recovery check.

The service combines store-side aggregate signals with public release and
issue evidence. It does not collect customer, order, payment, or raw log
content.

## Beta status

The hosted service is a free beta. Accuracy on real stores is still
unmeasured, so the tools can abstain or return limited confidence when the
available evidence is incomplete. The service does not make changes to a
store.

## Install

This repository follows the Agent Plugins open standard. Clients that support
Agent Plugins can read `plugin.json` and `mcp.json` directly. The MCP endpoint
uses Streamable HTTP:

`https://revenue-graph.utilityhouse.xyz/mcp/registry`

Product information and setup guidance are available at
https://revenue-graph.utilityhouse.xyz/.

## License

The plugin metadata in this repository is available under the MIT License.
The hosted service and its data remain subject to the terms published on the
product website.
