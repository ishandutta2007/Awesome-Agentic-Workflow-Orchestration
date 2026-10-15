# Awesome-Agentic-Workflow-Orchestration

## Top Agentic Workflow Orchestration Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Multi-Agent Orchestration, Stateful LLM Workflows, Enterprise AI Agents & Tool-Using Automation*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Agentic Workflow Orchestration**. These systems coordinate multi-step, multi-actor AI agents that use tools, maintain state, call APIs, and complete complex business processes—from customer support to internal automation and knowledge work.



**Examples** include Microsoft Copilot Studio, ServiceNow Now Assist, Salesforce Agentforce, Amazon Bedrock Agents, Google Vertex Agents, Moveworks, Amelia, Ada, Cognigy, and Kore.ai (the category leaders).



**Open-source emphasis**: The agentic orchestration layer is rich in open-source frameworks. **LangGraph**, **CrewAI**, **Microsoft Agent Framework**, **LlamaIndex Workflows**, **Temporal**, and related projects enable fully controllable, self-hosted agentic systems. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Microsoft Copilot Studio](https://www.microsoft.com/en-us/microsoft-copilot/microsoft-copilot-studio)**  

  Low-code platform for building, testing, and deploying custom AI agents and copilots integrated with Microsoft 365, Power Platform, and enterprise data sources.



- **[ServiceNow Now Assist](https://www.servicenow.com/products/now-assist.html)**  

  Generative AI and agent capabilities embedded in the ServiceNow platform for IT, customer service, HR, and workflow automation.



- **[Salesforce Agentforce](https://www.salesforce.com/agentforce/)**  

  Salesforce’s agentic layer for building autonomous and assisted agents across sales, service, marketing, and commerce clouds.



- **[Amazon Bedrock Agents](https://aws.amazon.com/bedrock/agents/)**  

  Fully managed service on Amazon Bedrock for creating agents that plan, call APIs/tools, and complete multi-step tasks using foundation models.



- **[Google Vertex AI Agents](https://cloud.google.com/vertex-ai)**  

  Agent building and orchestration capabilities within Vertex AI for enterprise generative AI applications on Google Cloud.



- **[Moveworks](https://www.moveworks.com/)**  

  Enterprise AI assistant platform focused on employee support, IT service management, and cross-system workflow automation.



- **[Amelia](https://amelia.com/)**  

  Conversational AI and intelligent automation platform for customer service and enterprise process automation.



- **[Ada](https://www.ada.cx/)**  

  Customer service AI agent platform specializing in automated support, brand-aligned conversations, and escalation handling.



- **[Cognigy](https://www.cognigy.com/)**  

  Enterprise conversational AI platform for building voice and chat agents with advanced dialogue management and integrations.



- **[Kore.ai](https://kore.ai/)**  

  AI agent and virtual assistant platform for enterprise customer experience and employee experience use cases.



## Open-Source GitHub Projects

- **[LangGraph](https://github.com/langchain-ai/langgraph)**  

  Low-level orchestration framework for building stateful, multi-actor applications with LLMs—supporting cycles, branching, persistence, human-in-the-loop, and production-grade agent workflows.



- **[CrewAI](https://github.com/crewAIInc/crewAI)**  

  Open-source multi-agent framework for defining role-based agents, tasks, and crews that collaborate to complete complex workflows.



- **[Microsoft Agent Framework](https://github.com/microsoft/agent-framework)**  

  Open multi-language framework for production-grade AI agents and multi-agent workflows (evolution of ideas from AutoGen and Semantic Kernel).



- **[LlamaIndex Workflows / Agents](https://github.com/run-llama/llama_index)**  

  Event-driven workflow and agent abstractions for building retrieval-augmented and tool-using agentic applications.



- **[Temporal](https://github.com/temporalio/temporal)**  

  Durable execution platform widely used to orchestrate long-running, reliable workflows—including agentic and LLM-powered processes.



- **[Prefect](https://github.com/PrefectHQ/prefect)**  

  Modern workflow orchestration engine that can coordinate data and agent pipelines with dynamic, observable runs.



- **[Dagster](https://github.com/dagster-io/dagster)**  

  Data-aware orchestration platform increasingly used to schedule and monitor LLM and agent pipelines as assets.



- **[AutoGen](https://github.com/microsoft/autogen)**  

  Multi-agent conversation framework (largely in maintenance mode; many teams migrating toward Microsoft Agent Framework).



- **[n8n](https://github.com/n8n-io/n8n)**  

  Open-source workflow automation tool with AI/agent nodes for connecting LLMs to hundreds of services.



- **[Documentation and LangGraph / CrewAI guides](https://langchain-ai.github.io/langgraph/)**  

  Official documentation, tutorials, and production patterns for building reliable agentic systems with open frameworks.



### Additional Strong Open-Source Options

- Using **LangGraph** for explicit, stateful, long-running agent graphs with checkpointing and human review.

- Building role-based multi-agent teams quickly with **CrewAI**.

- Orchestrating durable agent processes with **Temporal** or data-centric pipelines with **Prefect** / **Dagster**.

- Combining open agent frameworks with self-hosted or open-weight models for privacy and cost control.

- Accepting that enterprise SaaS platforms (Copilot Studio, Agentforce, Bedrock Agents, ServiceNow Now Assist, etc.) still lead in governance, compliance, pre-built connectors, and turnkey deployment.



**Frameworks for building custom systems**: Orchestrate with **LangGraph** or **CrewAI** → add durable execution via **Temporal** if needed → connect tools and data sources → deploy behind your own APIs or UI. Suitable for engineering teams that want full control and observability. Many enterprises still adopt Microsoft, Salesforce, ServiceNow, or cloud-provider agent platforms for integrated security and support.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Agentic workflows can take real actions across systems. Implement proper authentication, sandboxing, audit logging, and human oversight. This list is not security, compliance, or architecture advice.



---

**Made for AI engineers, automation architects, and open-agent advocates.**

Let's keep agentic workflows reliable, transparent, and as open as practical.
