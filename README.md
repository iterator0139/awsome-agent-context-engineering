# awsome-agent-context-engineering

Curated resources on **agent context engineering**: long context and models, memory and external state, context assembly and compression, tools and multi-agent systems, open-source implementations, and survey papers. Project goals and editorial constraints are in [docs/init.md](docs/init.md).

## Maintenance principles

- **Verifiable**: Each entry must link to a primary, directly openable source (preprints, official docs or engineering blogs, upstream repository homepages). Avoid using reposts or commentary as the only citation.
- **Living list**: The field moves quickly; Issues and PRs are welcome to add links or fix descriptions.
- **Why it matters**: One or two sentences per item explaining relevance—not just a bare title.

## Paradigms and industry practice

| Resource | Summary | Link |
|----------|---------|------|
| Anthropic | Frames context engineering as **curating and maintaining** the right token set across multi-turn inference; covers context decay, system prompts, tools, and MCP | https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents |
| Anthropic | How to design tools agents can use effectively, with MCP as the through-line (tightly related to tool definitions in context) | https://www.anthropic.com/engineering/writing-tools-for-agents |
| Model Context Protocol | Open standard for connecting external data, tools, and workflows into model/agent context in a uniform way | https://modelcontextprotocol.io |

## Surveys and large curated paper lists

| Resource | Summary | Link |
|----------|---------|------|
| *A Survey of Context Engineering for Large Language Models* | 2025 survey: formalizes context engineering into **components** (retrieval & generation, processing, management) and **system implementations** (RAG, memory, tool use, multi-agent); analyzes 1400+ papers | https://arxiv.org/abs/2507.13334 |
| Awesome-Context-Engineering | Companion awesome list and code index maintained by the survey authors | https://github.com/Meirtz/Awesome-Context-Engineering |

## Agent memory and long-term context (surveys)

| Resource | Summary | Link |
|----------|---------|------|
| *Memory for Autonomous LLM Agents: Mechanisms, Evaluation, and Emerging Frontiers* | Survey of autonomous agent memory: mechanisms, evaluation, and open problems | https://arxiv.org/abs/2603.07670 |
| *From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms* | Evolutionary framing from storage to experience; authors maintain an updated paper and resource list | https://arxiv.org/html/2605.06716 · https://github.com/FeishuLuo/Evolving-LLM-Agent-Memory-Survey |
| *LLM Agent Memory: A Survey from a Unified Representation--Management Perspective* | Survey from a unified representation–management perspective (OpenReview page) | https://openreview.net/forum?id=KPs1EgGKcT |

## Open-source frameworks and products (memory / stateful agents)

| Resource | Summary | Link |
|----------|---------|------|
| Letta | Stateful agent platform (MemGPT lineage); emphasizes editable memory blocks and hierarchical memory | https://github.com/letta-ai/letta |
| Mem0 | General-purpose memory layer across sessions; integrates with multiple agent stacks | https://github.com/mem0ai/mem0 |
| LangMem | LangChain-side memory tools and background management for LangGraph | https://github.com/langchain-ai/langmem |
| LangGraph | Graph-based orchestration for multi-step and looping agent workflows (closely tied to context assembly and checkpoints) | https://github.com/langchain-ai/langgraph |
| Zep | Long-term memory and conversational context product (graph and fact extraction, etc.—see vendor docs) | https://github.com/getzep/zep |

## Contributing

For new entries, include a **primary link** and a single factual sentence. If you state versions, numbers, or benchmarks, tie them to the linked source or another verifiable reference.
