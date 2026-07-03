# Hi, I'm Ajay 👋

Software engineer at [Equal](https://equal.in) (Hyderabad) · IIT Hyderabad '24

I build backend systems and AI workflows — Java/Spring Boot microservices on one side, Python/LLM pipelines on the other, all of it on AWS.

## What I work on

Most of my work lives in Equal's private repos, where I've built and shipped:

- **A legal / court-records verification engine** — crawls and indexes 200M+ Indian eCourts records into an S3 + Parquet data lake (Athena), then runs a layered matching pipeline: deterministic fuzzy scoring to narrow millions of candidates, an LLM (AWS Bedrock) to adjudicate hard same-person matches, and a rules layer for legally-critical severity classification. Replaced external vendors — days → ~15 minutes, at ~5% of the cost.
- **A multi-agent insufficiency-resolution system** — AI agents (Bedrock, Agno) that detect missing verification data, then chase it via LLM-drafted emails, AI voice calls (Ultravox), and an MCP-based OCR service (Textract). Cut manual handling ~60%.
- **An internal LLM chatbot** for Equal's console — tool-calling across verifications, notifications, and ticketing; resolves ~30% of HR-support queries end to end.
- **A dynamic routing library** — rule-based provider selection (default / override / weighted / context-aware) with circuit breaking and caching, UI-configurable so ops can change routing without a deploy. Pushed verification success from 80% → 90%; now one of several shared libraries I've written that run across 12+ microservices.

## Public projects

| Project | What it is |
|---|---|
| [magicthon](https://github.com/ajaypatel0905/magicthon) | Vision-LLM meme maker built in a day for the Magicthon hackathon (Next.js, Supabase) — advanced to the interview round |
| [neustack-ecommerce](https://github.com/ajaypatel0905/neustack-ecommerce) | E-commerce backend with an nth-order reward-discount system — TypeScript/Express, layered architecture, fully tested |
| [redrob-signalrank](https://github.com/ajaypatel0905/redrob-signalrank) | Hybrid candidate ranker that reads profiles instead of matching keywords (Python) |

## Stack

`Java` `Spring Boot` `Python` `FastAPI` `TypeScript` `React/Next.js` · `AWS` (Lambda, DynamoDB, SQS/SNS, S3, Athena, Bedrock, ECS, CDK) · `gRPC` `Docker` `Prometheus/Grafana` · LLM tooling: RAG, MCP, multi-agent orchestration

## Reach me

[LinkedIn](https://www.linkedin.com/in/ajaypatel0905) · ajaypatel39995@gmail.com
