# Anondevnet

**Applied AI / LLM Engineer | RAG, Agents, Evals, AI Security**

I ship evaluated RAG and agent systems in Python: a live cited-RAG demo (mean recall@5 0.84, citation and refusal accuracy 1.0), a LangGraph + MCP research agent with forecast back-tests, and an LLM-assisted auditor benchmarked on 243 labeled contracts. Builds use FastAPI, Docker, CI eval gates, and sandbox guards.

Local-first systems that rank, draft, retrieve, or audit information, then stop at a clear gate before anything goes live. Paid and live API paths stay opt-in, and the READMEs say what has and has not been tested. 12 public AI and software repositories, including 2 live demos on Render.

## Featured projects

| Project | What it is | Stack |
|---|---|---|
| [audit-rag-assistant](https://github.com/Anondevnet/audit-rag-assistant) | Cited RAG assistant over a license-cleared smart-contract weakness corpus, with a [live demo](https://audit-rag-assistant.onrender.com/). Mean recall@5 raised from 0.42 to 0.84 and MRR@5 from 0.51 to 0.72 via chunking, query expansion, and reranker tuning; citation and refusal accuracy 1.0 on a 20-question golden set. | Python, FastAPI, SQLite FTS5, sqlite-vec |
| [contract-auditor](https://github.com/Anondevnet/contract-auditor) | Local-first Solidity auditor that labels every claim FACT, INFERENCE, HYPOTHESIS, UNKNOWN, or AI_OPINION so LLM text cannot confirm a finding by itself. [Live demo](https://contract-auditor-cgw5.onrender.com/). Paste-only with per-IP rate limits; 1,000+ tests in CI. | Python, FastAPI, Slither, Docker |
| [auditor-evals](https://github.com/Anondevnet/auditor-evals) | Reproducible eval harness (pinned datasets, SHA-256 manifests, fixed seed) on 243 labeled contracts. Slither + local Qwen 9B reached line-level F1 0.317 vs 0.312 for Slither alone and cut clean-contract false positives from 0.78 to 0.68. | Python, Ollama, Slither |
| [polymarket-research-agent](https://github.com/Anondevnet/polymarket-research-agent) | Read-only LangGraph research agent with hybrid RAG, an MCP server, and forecast evals against resolved markets (Brier, log loss, ECE). Hybrid recall@5 0.9375 on a 16-query labeled set with a CI gate at 0.8; 59 tests. | Python, FastAPI, LangGraph, Qdrant |
| [issue-to-pr-agent](https://github.com/Anondevnet/issue-to-pr-agent) | Local coding agent that must reproduce a GitHub issue with a failing test before editing code, then patches and retests in a Docker sandbox (no network, read-only root). 15-task real-bug benchmark built and verified; full run pending. | Python, Ollama, Docker |
| [trend-intelligence](https://github.com/Anondevnet/trend-intelligence) | Append-only signal history with point-in-time backtests; Claude client with routing, budget caps, and caching; approval-gated drafts, posting off by default (231 tests). | Python, SQLite, Anthropic |

Also on this profile: [telegram-content-intelligence](https://github.com/Anondevnet/telegram-content-intelligence) (RSS-to-Telegram queue with gated no-LLM drafts, 189 tests) and [ai-video-pipeline](https://github.com/Anondevnet/ai-video-pipeline) (restartable short-form video pipeline with a Kling client and a tested ffmpeg mock mode, 75 tests).

## Tech stack

Python, FastAPI, Pydantic, LangGraph, MCP, Qdrant, sqlite-vec, SQLite, Docker, Terraform, GitHub Actions, pytest, Slither, Ollama, Langfuse, OpenTelemetry, and the Anthropic, Gemini, and OpenAI-compatible APIs (live calls off by default).

## Open to work

Open to remote roles in applied AI and LLM engineering, AI automation, and AI security.

[LinkedIn](https://www.linkedin.com/in/anon-devnet-b158b2446/)
