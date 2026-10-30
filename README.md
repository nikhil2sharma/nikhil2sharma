### Hi, I'm Nikhil Sharma

**AI Agent Engineer · Telecom Core (4G/5G) · LLM Automation**

I build AI agents that do real operational work: they call tools, read live data
and explain what they found, instead of guessing. My background is in telecom core
networks (4G EPC / 5G core), so a lot of what I build is aimed at network
operations, where the data is noisy and the answers need to be right.

**Open to freelance projects, consulting and full-time AI engineering roles.**

---

#### Featured projects

**[telecom-noc-agent](https://github.com/nikhil2sharma/telecom-noc-agent)**
A NOC assistant for a 4G EPC core. Network KPIs are exposed to Claude as MCP tools,
so it can run health checks and write a root-cause analysis (for example, tracing a
PGW session-success drop to GTP echo timeouts) from tool data.
`Claude Agent SDK` `MCP` `Python` `pytest` `GitHub Actions`

**[churn-prediction-api](https://github.com/nikhil2sharma/churn-prediction-api)**
An end-to-end ML service: a scikit-learn training pipeline with a quality gate
(the model isn't saved unless ROC AUC ≥ 0.70) and a FastAPI app that serves it,
packaged with Docker. Current model: ROC AUC 0.82 on held-out data.
`scikit-learn` `FastAPI` `Pydantic` `Docker` `GitHub Actions`

**[version-agent](https://github.com/nikhil2sharma/version-agent)**
Give it a CSV of tools and the versions you run; it uses Claude with web search to
find each tool's latest stable release and writes a report of what's out of date.
`Anthropic API` `web search tool` `Python` `CLI`

Every project has tests, CI (lint, tests, secret scan) and a README you can run
from top to bottom.

---

#### Tech stack

- **AI / LLM:** Claude Agent SDK, Anthropic API, MCP (Model Context Protocol), tool-calling agents, prompt engineering
- **ML:** scikit-learn, pandas, NumPy, Jupyter
- **Backend:** Python, FastAPI, REST APIs, Django
- **DevOps:** Docker, GitHub Actions, Git, Linux, uv
- **Domain:** Telecom 4G EPC / 5G core, network operations (NOC)

---

#### What I can help with

- Custom AI agents and LLM integrations connected to your own tools and data
- Network-operations automation for telecom and ISP teams
- ML models packaged as tested, deployable APIs

**Contact:** [nikhil.sharma001@gmail.com](mailto:nikhil.sharma001@gmail.com)
