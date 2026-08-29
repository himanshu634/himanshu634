<!--
BEFORE PUBLISHING
1. Replace YOUR-HANDLE in the LinkedIn link at the bottom.
2. Read the Maester and Bull Agritech sections and swap general phrasing for specifics where you can.
3. In GitHub profile settings, change company from "Genuin Inc." to "Bull Agritech"
   and fix the location typo ("Ahemdabad" -> "Ahmedabad").
HTML comments like this one do not render on GitHub, so you can leave them in.
-->

# Hi, I'm Himanshu 👋

**Full-stack & AI engineer building software for money and markets.**

I'm a software engineer in Ahmedabad, India. I started on the frontend and kept following problems downward: state management, then backend and data, then Rust, and now LLM agents. Most of what I build ends up being about money or markets. A banking ledger I wrote to learn Rust, an open-source Splitwise alternative, the commodity supply-chain platform I work on at Bull Agritech, and now Maester, a portfolio risk platform.

## Now

- 📈 **Maester**: an AI-driven portfolio risk management platform. Details below.
- 🏢 **Bull Agritech**: engineer at a seed-stage agritech in Ahmedabad. Agents that run our lead pipeline today, and Koshi, an AI product for agro retailers, next. Details below.
- 🦀 **Rust**: systems programming through CLI tools, to get comfortable with ownership, lifetimes and code where latency matters.
- 🧠 **AI systems**: multi-agent orchestration, RAG pipelines and vector databases. Most of this feeds Maester and the agents we run at Bull Agritech.

<!--
MAESTER: this section is written from your own description of the project.
Fintech readers respond to specifics (data sources, which risk measures, how many
agents, what ships next), so replace general phrasing with concrete details wherever
you can. The third bullet is my suggestion of what a finance audience looks for;
keep it only if it reflects work you've done.
-->

## Maester

Maester reads a portfolio as a whole and answers the questions most tools skip: how good is this portfolio, where is the risk, and what in the market right now should change my view of it. Analysis runs through AI-driven insights rather than a fixed set of screens.

What I'm working through:

- **Multi-agent orchestration.** Splitting analysis across specialised agents with narrow jobs instead of one giant prompt, then coordinating their output into a single view.
- **RAG over market context.** Retrieval over documents and market data with PostgreSQL + pgvector, so the model reasons from sources rather than from training data.
- **Keeping the output honest.** Grounding, structured outputs and guardrails. In finance a confident wrong number costs more than no number.

Stack: TypeScript, Next.js, Node.js, PostgreSQL + pgvector, Python for the analysis side.
<!-- Confirm this stack line matches Maester. Remove Python if it isn't in there. -->

Private while I get the core right. Progress notes go on X.

<!--
BULL AGRITECH: written from your description. Two places where a specific will land
better than a general sentence: (1) name what each CRM agent does, e.g. qualifies,
follows up, scores, schedules; (2) say where Koshi's insights come from, e.g. sales
history, inventory, crop calendars. Also check that the "seeds, fertiliser and crop
protection" gloss matches who Koshi serves, and add what you personally own.
The "over 6,000 farmers" figure comes from a Jan 2025 press piece; update or remove it.
-->

## Bull Agritech

Seed-stage agritech in Ahmedabad. Small team, so I work across the whole product, from the UI down to the database.

What we're building:

- **The supply-chain platform.** Connects farmers directly to commodity processors and handles price discovery, logistics, quality checks and payment protection in between. Over 6,000 farmers sell through it instead of their local APMC.
- **An agent-run CRM.** Our internal CRM, where multiple agents, each with its own job, manage the lead pipeline.
- **Koshi.** Where we're headed next: an AI application for agro retailers, the shops that sell farmers their seeds, fertiliser and crop protection. Koshi turns the shop into an AI-insight-driven business, so the retailer catches every upsell opportunity.

## Stack

| Area | What I use |
|---|---|
| **Languages** | TypeScript, Rust, Python, JavaScript |
| **Frontend** | React, Next.js, Tailwind CSS, Zustand / Redux |
| **Backend & data** | Node.js, Express, PostgreSQL, Supabase, pgvector |
| **AI** | LLM integrations, RAG pipelines, multi-agent orchestration, vector search |
| **Practice** | System architecture, REST / GraphQL API design, monorepos |

<!-- Optional: apmc_management (Dart) fits the "markets" thread if you're happy showing it. -->

## GitHub

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=himanshu634&show_icons=true&theme=radical&hide_border=true" alt="Himanshu's GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=himanshu634&layout=compact&theme=radical&hide_border=true" alt="Top languages" />
</p>

## Contact

If you're building something in markets, trading or fintech and need an engineer who can own a product end to end, my DMs are open.

- **X:** [@himanshu_btw](https://twitter.com/himanshu_btw)
- **LinkedIn:** [linkedin.com/in/YOUR-HANDLE](https://www.linkedin.com/in/himanshu-mendapara/) <!-- replace YOUR-HANDLE before publishing -->
- **Email:** [himanshumendapra@gmail.com](mailto:himanshumendapra@gmail.com)
