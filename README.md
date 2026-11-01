# Hi, I'm Himanshu 👋

I build AI agents and the software around them. This is where I experiment: document AI over financial filings, graph memory for agents, and agents that keep running long after you close the tab.

## 📈 Maester

**[Maester](https://github.com/himanshu634/maester)** is my main project: an open-source portfolio manager for long-term investors, India-first and self-hostable. It watches your holdings, filings and prices, and tells you which decision is due, with the evidence behind it.

One rule runs through it: **the model reads, code calculates, and every number cites its source.**

What's under the hood:

- **Document AI over annual reports.** Docling and RapidOCR turn report PDFs into searchable chunks. XBRL filings are parsed alongside, and each filing's PDF and XBRL stay paired.
- **LangGraph extraction.** Finds the statement pages, fans out one branch per statement with `Send`, then loops extract → deterministic arithmetic check → targeted correction. Retries, a model-call budget, and bad corrections get rejected. Claude with structured outputs.
- **Hybrid RAG.** pgvector HNSW over `halfvec(1024)` plus Postgres full-text search, fused with reciprocal rank fusion. A gate refuses queries when the embedding service serves a different model than the one the index was built with.
- **Provenance on every figure.** The filing, page, unit, period and reporting basis. Missing data shows as unknown, never as zero.
- **Evals.** `maester-eval` runs offline with dev and held-out splits. On held-out banks: 1,521 statement-sum checks across 65 filings, none failed.
- **MCP server.** Seven typed, read-only tools, so AI assistants answer from your filings with cited figures.
- **Data.** A 4,675-file BSE filings corpus (13 GB of PDFs and XBRL), plus read-only Zerodha holdings.

**Next:** named, versioned calculations (a margin is a calculation you can inspect, never a model's arithmetic), then return tracking, then autonomous monitoring that suggests and explains but never trades.

TypeScript, Hono, Drizzle, Zod, SvelteKit, Python, LangGraph, Postgres + pgvector. AGPL, pre-alpha, built in public.

## 🤖 AI agents and other experiments

The thread through all of it: agents you can trust with real data.

- **[Citadel](https://github.com/himanshu634/citadel)**: a company brain on FalkorDB. Graph RAG with multi-agent memory, 22 reviewed Cypher tools, and a grounding check that rejects any citation the agent never saw. When the graph can't answer, a Keeper agent researches the gap and writes the fix back. Built in 3 days for Graph Hacks (FalkorDB × WeMakeDevs); passes 119 of 120 graded eval runs.
- **[Insider](https://github.com/himanshu634/Insider)**: turns trader WhatsApp groups into clean, comparable mandi prices and a daily brief for commodity buyers. Gujarati and English.
- **Claude Code** is how I build: skill libraries, reviewer subagents, hooks. Side quest: **Tank**, a macOS menu bar app that moves Claude Code sessions between accounts (private for now).

## 📚 Learning now

- **Agents in production for long-running tasks.** Durable execution and checkpoints, so a run survives a crash and resumes where it stopped. Human approval in the middle of a run. Retries, budgets and timeouts. Tracing what an agent did, after the fact. Maester's autonomous monitoring is where this lands.
- **Graph databases.** FalkorDB and Cypher, graph RAG, and when a graph answers what a vector index can't. Citadel was the first step.
- **Vectors.** HNSW tuning, half-precision embeddings, hybrid search and reranking, and keeping an index in step with the model that embedded it.

## 🐙 GitHub

Open source: I wrote the Trino connector for [WrenAI](https://github.com/Canner/WrenAI) and [wren-engine](https://github.com/Canner/wren-engine), and presented it on the Trino Community Broadcast (2024).

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=himanshu634&show_icons=true&hide_border=true" alt="Himanshu's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=himanshu634&layout=compact&hide_border=true" alt="Top languages" />
</p>

## 📫 Say hi

[builtbyhimanshu.com](https://builtbyhimanshu.com) · [LinkedIn](https://www.linkedin.com/in/himanshu-mendapara/) · [X](https://x.com/himanshu_btw) · [Email](mailto:himanshumendapra@gmail.com)
