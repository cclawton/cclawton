# Craig Lawton

I build agentic systems, evaluate foundation models for Australian regulated sectors, and use AI as a creative instrument. The three connect: I evaluate the models, orchestrate the agents, and put the output to work.

---

## Agentic systems

Headless autonomous loops running on a Mac mini — workers that produce, a supervisor that triages, Signal for delivery. No dashboards, no polling.

- **[supervisor](https://github.com/cclawton/supervisor)** — two-layer producer/verifier architecture. Workers write run files; a separate triage agent classifies them and signals only when something actually matters. Integrates with any tool that writes to the filesystem — Obsidian, CI, scrapers, task managers.
- **[bullpen](https://github.com/cclawton/bullpen)** — profile-driven content pipeline using Claude Code subagents. Researcher, drafter, rhythm polisher, trimmer, safety reviewer, image prompter — each with a distinct role. Voice and constraints are config, not code.
- **[podcastindex-mcp-server](https://github.com/cclawton/podcastindex-mcp-server)** — MCP server for the Podcast Index API. Exposes search, episode lookup, and feed discovery as tools any MCP-aware agent can call.

---

## Sovereign AI evaluation

Foundation models don't behave the same in Australian healthcare, government, or financial services as they do on leaderboards. Hexapla is the measurement layer for that gap.

- **[hexapla](https://github.com/cclawton/hexapla)** — evaluation framework and manifesto for the foundation-model era in Australia. Domain-adapted benchmarks, novel backends, Australian regulatory context. Built on the belief that measurement precedes trust.

---

## AI creative

Writing and music are the same problem: structure, voice, and knowing when to stop. I use AI as a collaborator on both.

- **[bullpen](https://github.com/cclawton/bullpen)** — the writing side. Multi-agent pipeline from research through publication, with per-profile voice configuration.
- **[asian-sentry-techniques](https://github.com/cclawton/asian-sentry-techniques)** — the music side. Orchestration and composition notes from working in Logic Pro with foundation models. AI as co-composer, not autocomplete.
- **[music21-mcp](https://github.com/cclawton/music21-mcp)** — MCP server exposing 16 music21 MIDI tools to AI agents. Key detection, chord analysis, transposition, velocity, quantization, reharmonization, melody extraction, form analysis, and pattern search. Spec-driven, TDD, 120 tests.
- **[reascript-mcp](https://github.com/cclawton/reascript-mcp)** — MCP server for Reaper/ReaScript project control and state readback. Parses `.rpp` projects, generates Lua ReaScripts, and writes smoke-test scripts for REAPER execution. The DAW execution layer for the agentic music stack.

---

## Writing

I write about AI deployment in Australian regulated sectors, sovereign infrastructure, and building with agents at [craiglawton.com](https://craiglawton.com). AWS-affiliated — I disclaim my role, not my opinions.

---

## Connect

- Blog: [craiglawton.com](https://craiglawton.com)
- LinkedIn: [linkedin.com/in/craiglawton](https://linkedin.com/in/craiglawton)
- Podcast: [Building a Better Geek](https://buildingabettergeek.com)

