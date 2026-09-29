<p align="center">
  <a href="https://www.agentlist.io"><img src="media/banner.png" width="800" alt="Awesome Agent Orchestration — Frameworks and visual tools for agent coordination, durable workflows, and human approvals."></a>
</p>

# Awesome Agent Orchestration

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-f04424.svg)](CONTRIBUTING.md) [![CC0](https://img.shields.io/badge/license-CC0_1.0-6b6a64.svg)](LICENSE)

> Frameworks and visual tools for agent coordination, durable workflows, and human approvals.

12 projects · Upstream documentation checked 2026-09-29. Curated by [agentlist.io](https://www.agentlist.io).

Tools that compose agent steps, delegate work, or manage multi-agent workflows. Coding-agent clients and model-routing gateways are separate categories. Frameworks require application code; visual builders provide an authoring interface.

## Contents

- [How to choose](#how-to-choose)
- [Code-first frameworks](#code-first-frameworks)
- [Visual workflow builders](#visual-workflow-builders)
- [Maintenance and migration references](#maintenance-and-migration-references)
- [Related awesome lists](#related-awesome-lists)
- [More from Agentlist](#more-from-agentlist)
- [Contributing](#contributing)

## How to choose

- Does it coordinate tool calls, multiple agents, deterministic workflow steps, or all three?
- Can work pause for approval, recover from a failure, and resume with its state intact?
- Which parts run locally, on your infrastructure, or in a vendor-managed service?

## Code-first frameworks

- [Agno](https://github.com/agno-agi/agno) - Python framework for building agents, teams, and workflows. **Python framework.**
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for composing role-based agent teams and execution flows. **Python framework.**
- [Google ADK](https://github.com/google/adk-python) - Python toolkit for composing agents and workflow execution. **Python SDK.**
- [LangGraph](https://github.com/langchain-ai/langgraph) - Graph-based orchestration framework for long-running, stateful agent workflows. **Python and JavaScript.**
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript framework with agents, workflows, and suspend-and-resume execution. **TypeScript framework.**
- [Microsoft Agent Framework](https://github.com/microsoft/agent-framework) - Framework for building agents and multi-agent workflows in Python and .NET. **Python and .NET.**
- [OpenAI Agents SDK](https://github.com/openai/openai-agents-python) - Python SDK for agent workflows with tools, handoffs, and tracing. **Python SDK.**
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Typed Python agent framework supporting tools and multi-agent application patterns. **Python framework.**
- [smolagents](https://github.com/huggingface/smolagents) - Agent library supporting code-based tool use and managed-agent composition. **Python library.**

## Visual workflow builders

- [Langflow](https://github.com/langflow-ai/langflow) - Visual authoring environment for agent workflows with API and MCP serving. **Visual builder.**
- [n8n](https://github.com/n8n-io/n8n) - Workflow automation platform combining AI agents, application integrations, and custom code. **Self-hosted or cloud.**

## Maintenance and migration references

- [AutoGen](https://github.com/microsoft/autogen) - Multi-agent framework in maintenance mode; upstream directs new development toward Microsoft Agent Framework. **Maintenance mode.**

## Related awesome lists

Independent collections for deeper discovery. These are references, not affiliations or endorsements.

- [Agent-Analytics/awesome-multi-agent-orchestrators](https://github.com/Agent-Analytics/awesome-multi-agent-orchestrators) - Directory of multi-agent orchestration platforms.
- [andyrewlee/awesome-agent-orchestrators](https://github.com/andyrewlee/awesome-agent-orchestrators) - Orchestrators for coding-agent workflows.
- [vivy-yi/awesome-agent-orchestration](https://github.com/vivy-yi/awesome-agent-orchestration) - Broader framework and multi-agent ecosystem collection.

## More from Agentlist

- [Awesome Agent List](https://github.com/AgentListIO/awesome-agent-list)
- [Awesome Personal Assistants](https://github.com/AgentListIO/awesome-personal-assistants)
- [Awesome Agent Clients](https://github.com/AgentListIO/awesome-agent-clients)
- [Awesome Agent Memory](https://github.com/AgentListIO/awesome-agent-memory)
- [Awesome Agent Sandboxes](https://github.com/AgentListIO/awesome-agent-sandboxes)
- [Awesome Agent Observability](https://github.com/AgentListIO/awesome-agent-observability)

**[Browse agents](https://www.agentlist.io/list-of-ai-agents) · [Compare agents](https://www.agentlist.io/compare) · [GitHub organization](https://github.com/AgentListIO)**

## Contributing

Missing something useful? Read the [contribution guide](CONTRIBUTING.md) and open an issue or pull request with an official source.

The machine-readable [list.json](list.json) includes a primary-source link and a documentation-check date for every entry. Descriptions are editorial summaries of upstream documentation; inclusion does not imply hands-on testing, a security audit, or endorsement. Hosted services and source code may have different terms.

To update the list, edit `list.json`, run `bun run build`, then `bun run check`. The README is generated; avoid editing it directly.

[CC0](LICENSE) applies to this list’s text and data. Linked projects retain their own licenses.
