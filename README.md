# Anondevnet

Applied AI / LLM engineer building retrieval, evaluation, and automation systems with explicit safety gates.

Local-first systems that rank, draft, retrieve, or audit information, then stop at a clear gate before anything goes live. Most of the work is in Python, with Rust and TypeScript where the problem needs them. Paid and live API paths stay opt-in, and the READMEs say what has and has not been tested.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [audit-rag-assistant](https://github.com/Anondevnet/audit-rag-assistant) | Cited RAG assistant over a license-cleared smart-contract weakness corpus, with a [live demo](https://audit-rag-assistant.onrender.com/). Mean recall@5 0.84, doc recall 1.0, citation and refusal accuracy 1.0 on 20 approved goldens. | Python, FastAPI, SQLite |
| [polymarket-research-agent](https://github.com/Anondevnet/polymarket-research-agent) | Read-only LangGraph research agent with RAG, an MCP server, and forecast evals against resolved markets. Offline CI: 59 tests passed on Python 3.11 and 3.12. | Python, FastAPI, LangGraph, Qdrant |
| [contract-auditor](https://github.com/Anondevnet/contract-auditor) | Local-first smart-contract auditor: paste Solidity, get Slither findings labeled FACT / INFERENCE / HYPOTHESIS / UNKNOWN / AI_OPINION. [Live demo](https://contract-auditor-cgw5.onrender.com). FastAPI, Docker, and CI. | Python, Solidity, SQLite |
| [telegram-content-intelligence](https://github.com/Anondevnet/telegram-content-intelligence) | RSS-to-Telegram queue and a gated content-intelligence pipeline with deterministic, no-LLM drafts (189 tests). | Python, SQLite |
| [trend-intelligence](https://github.com/Anondevnet/trend-intelligence) | Local-first crypto and AI trend platform: collect, score, backtest, and draft sourced reports with posting safeguards (231 tests). | Python, SQLite, Anthropic |
| [cyberintel-x](https://github.com/Anondevnet/cyberintel-x) | Local-first cybersecurity research environment with shared search, provenance, and AI retrieval (Phase 1 of 6). | Python, FastAPI, SQLite |

Also on this profile: [ai-video-pipeline](https://github.com/Anondevnet/ai-video-pipeline), a restartable short-form video pipeline with a Kling client and a tested ffmpeg mock mode (75 tests).

## Tech stack

Python, Rust, TypeScript, SQLite, FastAPI, Flask, Streamlit, LangGraph, MCP, Qdrant, OpenCV, ffmpeg, Docker, pytest, and the Anthropic API (live calls off by default).

## Open to work

Open to remote roles in applied AI and LLM engineering, AI automation, and AI security.

[LinkedIn](https://www.linkedin.com/in/anon-devnet-b158b2446/)
