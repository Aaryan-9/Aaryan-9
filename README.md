# Aaryan Singh

**SDE-1 at Cashfree Payments** · Building production agent infrastructure for one of India's largest payment gateways · IIIT Kota CSE '26

I build AI agent systems: multi-agent orchestration, zero-trust tool access, and developer tooling that ships to thousands of merchants.

## What I'm working on

**Merchant-facing conversational agent** at Cashfree, built end-to-end (React frontend, agent backend, security architecture). An edge layer resolves merchant identity from the dashboard JWT and scopes tool access per request through an MCP proxy, making cross-tenant data access structurally impossible. p50 latency 6s, streaming, voice input in 20+ vernacular languages.

**Multi-agent support automation** that auto-resolves ~55% of inbound merchant support tickets; I work on the agent orchestration and context pipeline layer.

## Open source

| Project | What it is |
|---|---|
| [agent-skills](https://github.com/cashfree/agent-skills) | CLI that scaffolds payment-integration context into Cursor/Claude Code. 200+ weekly downloads; cut median integration time from days to 7.7 minutes |
| [agent-tools-js](https://github.com/cashfree/agent-tools-js) | Framework-agnostic TypeScript SDK exposing Cashfree APIs as agent tools |
| [cashfree-here](https://www.npmjs.com/package/@cashfreepayments/cashfree-here) | PCI-DSS compliant MCP-UI plugin rendering payment widgets natively inside AI apps |
| [ai-slop-remover](https://github.com/Aaryan-9/ai-slop-remover) | Local-first CLI that detects the artifacts AI coding tools leave behind via deterministic AST analysis across 9 languages, then hands your agent a fix plan |
| [toolwire](https://github.com/Aaryan-9/toolwire) | Framework-agnostic tool registry for LLM agents with Zod validation |

## Earlier at Cashfree (SDE Intern, 2024–2026)

Architected a multi-agent orchestration system in Slack serving 200+ daily requests across five teams, with RBAC-gated tool calling over internal APIs, Redshift, Kibana, and a GraphDB. Cut data lookups from hours to under 30 seconds. Also built a Go pipeline that parsed alerting configs across 250+ microservices and auto-generated 550+ Jira tickets.

## Stack

`TypeScript` `Python` `Go` `MCP` `multi-agent orchestration` `RAG` `prompt caching` `LLM evals` `Kafka` `Docker` `Kubernetes` `Redshift` `ClickHouse` `PostgreSQL`

## Highlights

- Winner, Amdocs GenAI Graduate Hackathon 2024 (11,500+ participants)
- Amazon ML Summer School 2024 (top 3,000 of 90,000+ applicants)
- LeetCode Knight (1874), 750+ problems solved

## Reach me

[LinkedIn](https://www.linkedin.com/in/aaryan-anil-kumar-singh/) · [Portfolio](https://aaryan-singh.vercel.app/) · aaryansingh6051@gmail.com
