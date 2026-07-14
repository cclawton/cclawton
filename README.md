# Craig Lawton

I build agentic systems, evaluate foundation models for Australian regulated sectors, and use AI as a creative instrument. The three connect: I evaluate the models, orchestrate the agents, and put the output to work.

---

## Agentic systems

Headless autonomous loops running on a Mac mini — workers that produce, a supervisor that triages, Signal for delivery. No dashboards, no polling.

- **[supervisor](https://github.com/cclawton/supervisor)** — two-layer producer/verifier architecture. Workers write run files; a separate triage agent classifies them and signals only when something actually matters. Integrates with any tool that writes to the filesystem — Obsidian, CI, scrapers, task managers.
- **[bullpen](https://github.com/cclawton/bullpen)**: profile-driven writing pipeline with bounded OpenCode stages, role-specific model routing, transactional validation, and optional Claude Code agents for interactive use. Voice and constraints live in configuration.
- **[podcastindex-mcp-server](https://github.com/cclawton/podcastindex-mcp-server)** — MCP server for the Podcast Index API. Exposes search, episode lookup, and feed discovery as tools any MCP-aware agent can call.

---

## AI evaluation

Leaderboards are useful, but they do not tell you how a model behaves in a specific operating context. I am building tools that measure model performance against local tasks, constraints, and evidence.

- **[hexapla](https://github.com/cclawton/hexapla)**: early evaluation harness for running repeatable model tests, scoring outputs, and producing comparable result matrices.

---

## AI creative

Writing and music are the same problem: structure, voice, and knowing when to stop. I use AI as a collaborator on both.

- **[bullpen](https://github.com/cclawton/bullpen)**: the writing side. Bounded research, drafting, trimming, and safety stages run through an editor-controlled pipeline with profile-specific voice and model routing.
- **[asian-sentry-techniques](https://github.com/cclawton/asian-sentry-techniques)** — the music side. Orchestration and composition notes from working in Logic Pro with foundation models. AI as co-composer, not autocomplete.
- **[music21-mcp](https://github.com/cclawton/music21-mcp)** — MCP server exposing 16 music21 MIDI tools to AI agents. Key detection, chord analysis, transposition, velocity, quantization, reharmonization, melody extraction, form analysis, and pattern search. Spec-driven, TDD, 120 tests.
- **[preset-semantic](https://github.com/cclawton/preset-semantic)** — local-first semantic search for music-production presets across Helix, Arturia, and Decent Sampler. ChromaDB and sentence-transformer embeddings turn musical descriptions into loadable preset candidates through a CLI or MCP tool.
- **[reascript-mcp](https://github.com/cclawton/reascript-mcp)** — MCP server for Reaper/ReaScript project control and state readback. Parses `.rpp` projects, generates Lua ReaScripts, and writes smoke-test scripts for REAPER execution. The DAW execution layer for the agentic music stack.

---

## Writing

I write about AI deployment in Australian regulated sectors, sovereign infrastructure, and building with agents at [craiglawton.com](https://craiglawton.com). AWS-affiliated — I disclaim my role, not my opinions.

---

## Connect

- Blog: [craiglawton.com](https://craiglawton.com)
- LinkedIn: [linkedin.com/in/craiglawton](https://linkedin.com/in/craiglawton)
- Podcast: [Building a Better Geek](https://buildingabettergeek.com)

