# Olaniyi George - Backend & AI Systems Engineer

I build production systems that operate AI models inside real infrastructure, not wrappers around an API. Real-time audio pipelines, domain-driven backends, fintech-grade transaction handling.

**Currently:** open to senior backend / AI systems / founding engineer roles (remote, global).

---

## Flagship: Truefit.ai
Real-time AI voice interview platform. Candidates talk to an AI interviewer over a dual-channel WebRTC/WebSocket architecture; Gemini Live drives a tool-calling interview state machine with zero infrastructure dependencies in the core agent.

Engineering highlight: diagnosed and fixed a compound audio bug — a greedy queue-drain collapsing 40 chunks into one `recv()` call, layered with a pts-clock reset that corrupted frame pacing — which caused an infinite greeting loop that made the system unshippable. [Full writeup →](https://olaniyigeorge.vercel.app/dev-stories/69cad8f4a7ba63fe57bc87f1)

`FastAPI` `aiortc/WebRTC` `Gemini Live API` `PostgreSQL` `Redis` `Domain-driven design`

## CoopWise
Cooperative savings platform digitizing Ajo/Esusu for African groups - idempotent contribution/payout handling, a three-queue Celery system, AI-driven financial insights, and stablecoin escrow on Flow.

`FastAPI` `PostgreSQL` `Celery` `Redis` `Next.js` `Flow/Cadence` `Paystack`

## LockedIn
Habit-accountability platform with AI-verified consistency tracking.

`Next.js` `TypeScript` `LangChain`

---

## Stack
| | |
|---|---|
| **Backend** | Python · FastAPI · Django · Node.js · TypeScript |
| **Real-time** | WebRTC · WebSockets · Celery |
| **AI** | Gemini Live API · OpenAI API · LangChain · PydanticAI |
| **Data/Infra** | PostgreSQL · Redis · Docker · AWS · GCP · Railway/Vercel |

## Connect
[Portfolio](https://olaniyigeorge.vercel.app) · [LinkedIn](https://www.linkedin.com/in/abeleje-olaniyi) · olaniyigeorge77@gmail.com
