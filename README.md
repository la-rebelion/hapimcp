# HAPI MCP – Headless API for Model Context Protocol

**Stop rewriting systems for AI. Instantly turn your APIs into MCP servers.**

HAPI MCP lifts your OpenAPI catalog into MCP tools automatically, keeping design (OAS/Arazzo) and runtime (agents/LLMs) cleanly separated. Your existing APIs become AI-ready tools—no new business logic, no sidecar servers, no rework.

## Key Features

- **No rewrites:** Reuse 100% of your API logic. OpenAPI in, MCP tools out. No parallel codebase or shadow services.
- **Faster time-to-value:** Turn specs into agent-ready tools in minutes. Update the spec, ship new tools instantly.
- **Reduced risk:** Permissions, auth, rate limits, auditability are inherited from your APIs—governance without bolt-ons.
- **Scales with you:** [runMCP](https://run.mcp.com.ai) delivers serverless-like elasticity with long-running when needed. Cold-start fast, stay warm for throughput.
- **Deterministic orchestration:** OrcA plans and executes multi-tool tasks predictably—no brittle prompt chaining.
- **Vendor-neutral:** Works with any MCP client: ChatGPT, Claude, [QBot](https://qbot.mcp.com.ai), [chatMCP](https://chat.mcp.com.ai). OAS + MCP + Arazzo stay portable.

## How It Works

1. **Pick your API spec**
   - OpenAPI, Swagger, REST—HAPI CLI works with any API specification format.
   - Supports OpenAPI 3.0+, REST APIs, OAuth 2.0 Dynamic Client Registration.

2. **Run a single command**
   - One simple CLI command transforms your API into a usable MCP Server.
   - No complex setup, zero configuration, works anywhere, cross-platform.

3. **Use instantly**
   - Your API is now ready as a tool, AI agent, or testing interface.
   - MCP server ready, AI agent compatible, testing interface, developer experience friendly.

## Visual Pipeline

```
API Spec (swagger.json) → HAPI CLI → Usable Tool (AI-ready) ← MCP Clients
```

```
[ OpenAPI / Swagger ]       [ HAPI CLI ]        [ MCP Server ]
       (Your API)         →   (Transform)   →   (Usable Tool)
                                                 ↑          ↑
                                                 |          |
                                          [ ChatGPT ]  [ runMCP ]
                                          [ Claude  ]  [ OrcA   ]
                                          [ QBot    ]  [ chatMCP]
                                          [ Agents  ]
```

## Who Wins With HAPI

- **Executives:** Ship AI initiatives without ballooning cost. Keep teams focused on outcomes, not rewrites and integration sprawl.
- **Architects & PMs:** Design with OpenAPI/Arazzo, run with MCP. Clear contracts, policy inheritance, and versioned workflows keep risk low.
- **Engineers & Ops:** Deploy once. HAPI Server + runMCP scale tools; QBot/chatMCP give fast feedback; OrcA keeps executions deterministic.

## Your Stack, Already Wired

- [**HAPI Server:**](https://hapi.mcp.com.ai) Turns OpenAPI into MCP tools automatically—contracts stay in sync with your source of truth.
- [**runMCP:**](https://run.mcp.com.ai) Autoscaling execution and testing for MCP tools; cold-start fast, stay warm when workflows run long.
- [**QBot:**](https://qbot.mcp.com.ai) CLI TUI for power users to interact with MCP tools directly from terminal or scripts.
- [**chatMCP:**](https://chat.mcp.com.ai) Conversational client that speaks MCP natively for support, ops, and internal assistants.
- [**OrcA:**](https://orca.mcp.com.ai) Deterministic planning and orchestration for multi-tool tasks; no brittle prompt spaghetti.
- **Agents:** Build agentic systems from standard APIs—no custom glue. Connect MCP clients across platforms.

## Demos

- [Playlist with demos](https://www.youtube.com/playlist?list=PL7wYqDMFQYFOZuB1nNOfisbVzb1uHw1fz)
- New [HAPI MCP YT Channel](https://youtube.com/@hapi-mcp) with demos API-First and MCP

## Documentation

- [Explore the Docs](https://docs.mcp.com.ai)
- [See HAPI Server](https://hapi.mcp.com.ai)

## FAQ

- **Do we need to rewrite our services?**  
  No. HAPI MCP lifts your existing OpenAPI specs directly into MCP tools. Your auth, validation, and business rules remain unchanged.

- **Is this just another MCP server?**  
  It’s the **Headless API** model: your API becomes the runtime. HAPI Server reflects it as MCP; runMCP scales it; OrcA orchestrates it. No duplicate logic.

- **Which clients can consume the tools?**  
  Any MCP client: ChatGPT, Claude, QBot, chatMCP, bespoke orchestrators—vendor-neutral by design.

- **How do we keep control and compliance?**  
  Your API remains the single source of truth. Policies, RBAC, rate limits, and audit logs flow through automatically; **no shadow logic**.

- **What about security and privacy?**  
  Scoped credentials, per-tool permissions, and auditable calls are inherited from your API layer. HAPI adds guardrails and observability for regulated environments.

- **How fast can we get started?**  
  You can transform your first API into an MCP tool in less than five minutes. The HAPI CLI makes it quick and painless.

## Get Started

1. Install HAPI CLI from latest release: https://github.com/la-rebelion/hapimcp/releases
2. Transform your OpenAPI spec into an MCP server with a single command:
   ```bash
   hapi serve path/to/your/swagger.json --headless
   ```
3. Start using your MCP tools with any compatible client!

4. Explore the [documentation](https://docs.mcp.com.ai) for advanced usage and best practices.

## Contributing

Contributions are welcome! Open a discussion or submit a pull request on GitHub: https://github.com/la-rebelion/hapimcp

## License

HAPI MCP is licensed under the MIT License. See LICENSE for details.