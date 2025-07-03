# 🤖 AgentKits

**AgentKits** is a modular, agent-based operating system that simulates a full-service creative, technical, and AI-powered agency. Powered by the [OpenAI Agents SDK (Python)](https://openai.github.io/openai-agents-python/), each agent represents a real-world role — coordinated to plan, build, and deliver end-to-end execution.

> ✨ "It’s like hiring an entire agency — made of autonomous AI."

---

## 🧠 Why AgentKits?

AgentKits combines the power of LLM agents with real organizational roles and workflows — all orchestrated using OpenAI's native assistant & function-calling SDK.

- ✅ Built on OpenAI Assistants SDK (Node.js)  
- 🧩 60+ pre-defined agent roles across design, dev, marketing, and ops  
- 🔁 Agent-to-agent collaboration through tool-calling and workflows  
- ⚙️ Modular system: run one agent or an entire synthetic org  
- 🌐 Easily extensible via APIs, RAG, and vector search

---

## 🧰 What’s Inside

| Division                  | Example Agents                                |
|--------------------------|-----------------------------------------------|
| 🧠 Executive & Strategy   | Founder, CTO, COO, CMO                         |
| 🖼️ Creative & Design      | Brand Designer, Copywriter, Motion Designer    |
| 🌐 Web & Engineering      | Frontend, Backend, DevOps, SaaS Devs          |
| 🤖 AI & Agents            | Prompt Engineer, Agent Architect, LLM Dev     |
| 📈 Marketing & Growth     | SEO, Funnel Builder, Paid Ads, Community Lead |
| 🧳 Client Services & PM   | Account Manager, PM, Success Lead             |
| 🧰 Internal Tools & Labs  | Labs Lead, Automation Dev, Product Designer   |
| 📚 Knowledge & Enablement| Docs Creator, QA Tester, SOP Specialist       |
| 🧾 Finance & Legal        | Finance Manager, Billing Ops, Contract Lead   |

---

## ⚙️ Architecture

- `agents/` — assistant definitions, tools, and function interfaces  
- `workflows/` — multi-agent flows for execution (e.g. ship a brand)  
- `tools/` — real-world API connectors (Notion, Supabase, etc.)  
- `playground/` — test environment to interact with single/multi agents  
- `configs/` — prompt templates, memory configs, RAG options  

---

## 🚀 Use Cases

- Run a full creative AI team from a CLI or browser  
- Automate web builds, pitch decks, branding, or internal tools  
- Prototype agent workflows for client work or internal ops  
- Create new roles, custom tools, or agent coordination strategies

---

## 📦 Getting Started

```bash
git clone https://github.com/meltmagic/AgentKits.git
cd AgentKits
pip install -r requirements.txt
```

> ⚠️ Requires Node.js 18+ and access to OpenAI's Assistants API.

Configure your `.env`:

```
OPENAI_API_KEY=sk-...
```

---

## 🛠️ Roadmap

- [ ] 60+ agents defined via structured system prompts  
- [ ] Graph-based agent coordination  
- [ ] Web-based UI for workflow assembly  
- [ ] Prebuilt SaaS templates with agent plugins  
- [ ] OpenAI Assistants SDK: multi-agent orchestration layer

---

## 🤝 Contributing

PRs are welcome! Build new agents, tools, or workflows.  
Check `CONTRIBUTING.md` and open issues to get started.

---

## 📄 License

MIT License — open for remix, fork, and deploy.

---

## 🧙 Built by MeltMagic

An AI-native studio reimagining creative work, product dev, and internal systems with LLMs & automation.

> **AgentKits** — The future of work is autonomous, modular, and composable.
