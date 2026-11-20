<div align="center">

# Algen AI

**Governed AI agents, from prototype to production.**

[Website](https://algen.ai) · [Agent Runtime](https://github.com/AlgenAI/algen-agent-runtime) · [Agent Tools](https://github.com/AlgenAI/algen-agent-tools) · [Traccia](https://github.com/AlgenAI/traccia-py)

</div>

---

We build open-source infrastructure for AI agents that businesses can actually trust in production. Approvals, policies, budgets, audit trails and observability sit **in the agent's execution path**, so they are part of how the agent runs rather than something bolted on afterwards.

## Open-source projects

| Project | What it does |
|---|---|
| [**algen-agent-runtime**](https://github.com/AlgenAI/algen-agent-runtime) | Provider-neutral Python runtime for governed AI agents: human-in-the-loop approvals, policies, budgets, tenant isolation, audit and OpenTelemetry built in. |
| [**algen-agent-tools**](https://github.com/AlgenAI/algen-agent-tools) | Curated, governed connectors for agents built on the runtime: typed tools for email, documents, databases, messaging and MCP servers. |
| [**traccia-py**](https://github.com/AlgenAI/traccia-py) | OpenTelemetry-native observability, governance and compliance for AI agents and LLM applications. |
| [**agentstripes-reference-agent**](https://github.com/AlgenAI/agentstripes-reference-agent) | A reference support agent taken from prototype to production-ready, one capability at a time. |
| [**govern-slm**](https://github.com/AlgenAI/govern-slm) | Governed data construction and evaluation for small language models in text-to-SQL agents. |

## How the pieces fit

```
your agent ──► algen-agent-runtime ──► algen-agent-tools ──► email · docs · databases · MCP
                   │  approvals · policies · budgets · audit
                   └──► traccia (OpenTelemetry traces, governance, compliance)
```

## Get involved

- Star the repos you find useful. It helps others discover them.
- Found a bug or have an idea? Open an issue on the relevant repo.
- Contributions are welcome. Check each repo's README for setup and guidelines.

## Work with us

We help teams design, build and run governed AI agents in production. Reach out via [algen.ai](https://algen.ai).

<sub>Algen AI Private Limited</sub>
