# 500+ AI Agent Projects & Use Cases

Hi, my name is Saloni Bhatia. I'm passionate about AI agents and I've made this comprehensive collection of AI agent projects, use cases, and working implementations.

🚀 Quick Start • 🗺️ Browse Agents • 🏭 By Industry • 📊 Frameworks Compared

## What is this?

A curated collection of 500+ AI agent projects — production examples, tutorials, and working code spanning every major framework (LangGraph, CrewAI, AutoGen, Agno) and industry (Healthcare, Finance, Education, Cybersecurity, and more).

### Who it's for:

* Developers building their first or next AI agent
* Teams evaluating frameworks for production use
* Anyone looking to understand agent architectures from real examples

## ⚡ Quick Start

Pick a framework and run an agent in under 5 minutes:

```bash
# Run any agent from the agents/ directory
cd agents/01-web-research-agent
pip install -r requirements.txt
cp .env.example .env        # add your API key
python agent.py
```

All agents in `agents/` are self-contained with their own `requirements.txt` and `.env.example`.

## 🗺️ Navigation Guide

* **Run a working agent right now:** Go to `agents/`
* **Browse by AI framework:** Check the Framework-wise Use Cases below
* **Browse by industry:** Check the Industry Use Cases below
* **Learn with a course:** Go to `crewai_mcp_course/`

## 📊 Framework Comparison

Choosing a framework? Here's when to use each:

| Framework | Best For | Complexity | Multi-Agent | Streaming | Local LLM |
|---|---|---|---|---|---|
| **LangGraph** | Stateful workflows, RAG pipelines, complex graphs | ⭐⭐⭐ | ✅ | ✅ | ✅ |
| **CrewAI** | Role-based teams, business automation, rapid prototyping | ⭐⭐ | ✅ | ✅ | ✅ |
| **AutoGen** | Code generation, research, self-healing workflows | ⭐⭐⭐ | ✅ | ✅ | ✅ |
| **Agno** | Lightweight single agents, tool integration, fast iteration | ⭐ | ✅ | ✅ | ✅ |
| **LlamaIndex** | Document Q&A, enterprise RAG, data pipelines | ⭐⭐ | ⚠️ | ✅ | ✅ |

### Quick decision guide:

* Just starting out → Agno or CrewAI
* Need stateful graphs + RAG → LangGraph
* Building code-writing / research agents → AutoGen
* Enterprise document pipelines → LlamaIndex

## 🏭 Industry Use Cases

* **Healthcare:** HIA (Health Insights Agent), AI Health Assistant, Lina Egyptian Medical Chatbot
* **Finance:** Automated Trading Bot, Agent Wallet SDK, Financial Reasoning Agent
* **Education & Research:** Virtual AI Tutor, Research Scholar Agent, Study Partner
* **Cybersecurity:** Real-Time Threat Detection Agent, Vibe Hacking Agent (Red Team Testing)
* **Software Development:** Citadel (Orchestrating Claude Code agent fleets), Readme Generator Agent

## 🔧 Browse by Framework

### CrewAI (Role-based multi-agent framework)

* 📧 Email Auto Responder Flow
* 📝 Meeting Assistant Flow
* 🔄 Self Evaluation Loop Flow
* 📈 Lead Score Flow
* 📊 Marketing Strategy Generator
* 💹 Stock Analysis Tool
* 🔗 CrewAI + LangGraph Integration

### AutoGen (Microsoft's framework for code generation and multi-agent collaboration)

* 🤖 Automated Task Solving with Code Gen, Execution & Debugging
* 🤝 Group Chat (3 members, 1 manager)
* 📊 Data Visualization by Group Chat
* 🔄 Sequential Task-Solving
* 🧠 Solving Complex Tasks with Nested Chats
* 🌐 Web Search and SQL Database Interactions
* 🎨 Multimodal Agent with DALLE and GPT-4V

### Agno (Lightweight, fast agent framework)

* 🤖 Support Agent & Readme Generator Agent
* 🎥 YouTube Agent & Movie Recommendation Agent
* 📊 Finance Agent (Real-time stock insights & Yahoo Finance data)
* 🏠 MCP Airbnb Agent

### LangGraph (State-machine framework for complex, stateful workflows)

* 🤖 Chatbot Simulation Evaluation
* 🧠 Code Assistant with LangGraph (with iterative refinement)
* 🧑‍💼 Customer Support Agent
* 🔁 Extraction with Retries
* 🧠 Multi-Agent Workflow (Supervisor & Hierarchical Teams)
* 🧠 Corrective RAG (CRAG) & Self-RAG

## 📜 License

This repository is licensed under the MIT License.
