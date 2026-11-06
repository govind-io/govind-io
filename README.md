# Govind Sharma

**Staff Software Engineer** building AI agents and the distributed systems behind them.

I start from the business problem, pick the simplest design that holds up under retries and concurrency, and write the trade-offs down.

Mumbai, India · [govindio.com](https://www.govindio.com) · [LinkedIn](https://www.linkedin.com/in/govind-io/) · [Email](mailto:govindgovind852@gmail.com)

## Selected work

### [Stamina.io](https://stamina.io): AI sales, CRM and marketing SaaS

Joined as Founding Backend Engineer and was promoted to Staff Engineer and Head of Engineering. ARR grew from $250K to $2M+ in 9 months, with 1,000+ customers in 50+ countries.

- **Zara, an AI SDR agent:** built on LangGraph, it enriches 20K leads a day and doubled reply rates.
- **Workflow engine:** starts exactly one run per event on at-least-once delivery, across 5,000+ workflows a day.
- **Credit ledger:** idempotent usage billing with Stripe sync that survives late and duplicate webhooks.
- **LLM cost:** per-task model routing, held to quality by evals and guardrails, cut cost per lead by 70%.

### [FastBowlingLab](https://fastbowlinglab.com): founder and solo builder

An AI coaching app for fast bowlers. It runs MediaPipe pose estimation on phone video and turns it into annotated video and adaptive training plans. 1,200+ real users and 2,500+ deliveries analysed.

### NeshAI: engineering lead, via Better Software

Built an AI product recommendation engine for Fortune 500 sales teams, with LLM-powered retrieval over 1M+ documents, p95 retrieval under 800ms, MCP servers and SOC 2 controls.

### Loktantra Mediatech: tech lead

Built a self-hosted WebRTC platform on LiveKit, with a signaling server and React SDK, replacing a $2,000/month vendor. Scaled the platform to 100,000 concurrent users.

## Writing

- [How We Guarantee Exactly One Workflow Run per Event](https://www.govindio.com/blogs/exactly-one-workflow-run-per-event)
- [Why Our Credit Ledger Can't Double-Spend](https://www.govindio.com/blogs/credit-ledger-that-cannot-double-spend)
- [What It Takes to Keep Every Mailbox Inside Its Send Limits](https://www.govindio.com/blogs/per-mailbox-send-limits-at-scale)
- [Why One Analysis Ran Five Times: Idempotency at the Write](https://www.govindio.com/blogs/five-paid-runs-for-one-analysis)
- [How to Measure a Fast Bowler From Phone Video Without Lying](https://www.govindio.com/blogs/measuring-fast-bowlers-from-phone-video)

[All posts](https://www.govindio.com/blogs)

## Open source

- [livekit/components-js](https://github.com/livekit/components-js/pull/740): merged contribution to LiveKit's official React components.
- [tmb](https://github.com/govind-io/tmb): a CLI that generates modules from YAML-defined templates.

## Stack

- **AI:** LangGraph, LangChain, tool calling, structured outputs, MCP servers, LLM evals, guardrails, vector search, OpenAI, Anthropic Claude API
- **Backend and data:** TypeScript, Node.js, NestJS, Python, PostgreSQL, pgvector, Elasticsearch, Redis, Kafka, Google Pub/Sub, WebRTC
- **Cloud and reliability:** AWS, Kubernetes, Terraform, Docker, GitHub Actions, OpenTelemetry, Prometheus, Grafana
- **Frontend:** React, Next.js, React Native (Expo)
