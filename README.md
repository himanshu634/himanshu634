# Hi, I'm Himanshu 👋

I build AI agents and the software around them. This is where I experiment: graph memory for agents, document AI over financial filings, and whatever I'm learning next.

## 🤖 AI agents

The thread through all of it: agents you can trust with real data.

- **[Citadel](https://github.com/himanshu634/citadel)**: a company brain on FalkorDB. Graph RAG with multi-agent memory, 22 reviewed Cypher tools, and a grounding check that rejects any citation the agent never saw. When the graph can't answer, a Keeper agent researches the gap and writes the fix back. Built in 3 days for Graph Hacks (FalkorDB × WeMakeDevs); passes 119 of 120 graded eval runs.
- **MCP servers**: typed, read-only tools, so an assistant answers with cited figures instead of guesses.
- **Evals before trust**: dev and held-out splits, graded runs, LLM-as-judge.
- **Claude Code** is how I build: skill libraries, reviewer subagents, hooks. Side quest: **Tank**, a macOS menu bar app that moves Claude Code sessions between accounts (private for now).

## 📈 Maester

**[Maester](https://github.com/himanshu634/maester)** is an open-source portfolio manager for long-term investors: India-first and self-hostable. It watches your holdings, filings and prices, and tells you which decision is due, with the evidence behind it.

- Reads annual reports (PDF and XBRL) into structured statements. Every figure links to the page it came from.
- The model extracts; code does the arithmetic and checks that the lines add up.
- Hybrid search: pgvector and Postgres full-text, fused with reciprocal rank fusion.
- Reads your Zerodha holdings (read-only), and an MCP server lets AI assistants query your filings.

TypeScript, Hono, Drizzle, SvelteKit, Python, LangGraph, Postgres + pgvector. AGPL, pre-alpha.

## 🧪 Other experiments

- **[Insider](https://github.com/himanshu634/Insider)**: turns trader WhatsApp groups into clean, comparable mandi prices and a daily brief for commodity buyers. Gujarati and English.

## 📚 Learning now

- **Rust**: starting small with [simple-banking-cli](https://github.com/himanshu634/simple-banking-cli).
- **Solana**: [coin-launch](https://github.com/himanshu634/coin-launch), a token launch platform.
- **TLA+**: modelling race conditions and deadlocks before they reach code.
- **Graph databases**: FalkorDB and Cypher, through Citadel.

## 🐙 GitHub

Open source: I wrote the Trino connector for [WrenAI](https://github.com/Canner/WrenAI) and [wren-engine](https://github.com/Canner/wren-engine), and presented it on the Trino Community Broadcast (2024).

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=himanshu634&show_icons=true&hide_border=true" alt="Himanshu's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=himanshu634&layout=compact&hide_border=true" alt="Top languages" />
</p>

## 📫 Say hi

[builtbyhimanshu.com](https://builtbyhimanshu.com) · [LinkedIn](https://www.linkedin.com/in/himanshu-mendapara/) · [X](https://x.com/himanshu_btw) · [Email](mailto:himanshumendapra@gmail.com)
