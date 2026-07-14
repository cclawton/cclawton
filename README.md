# Craig Lawton

I build agentic systems, evaluate foundation models for Australian operating contexts, and make tools for creative work. The common thread is bounded systems, evidence, and keeping people in control.

---

## Agentic systems

Headless autonomous loops run on a Mac mini, with workers that produce, a supervisor that triages, and Signal for delivery. No dashboards or polling.

- **[supervisor](https://github.com/cclawton/supervisor)**: two-layer producer and verifier architecture. Workers write run files; a separate triage agent classifies them and signals only when something matters. It can integrate with any tool that writes to the filesystem, including Obsidian, CI, scrapers, and task managers.
- **[bullpen](https://github.com/cclawton/bullpen)**: profile-driven writing pipeline with bounded OpenCode stages, role-specific model routing, structural validation, and rollback on rejection. Optional Claude Code agents support a more flexible interactive workflow. The human editor controls publication.
- **[podcastindex-mcp-server](https://github.com/cclawton/podcastindex-mcp-server)**: Podcast Index search, episode lookup, and feed discovery exposed as MCP tools.

---

## Keeping models honest

Leaderboards are a starting point. I am interested in repeatable tests tied to local tasks, constraints, cost, and evidence.

- **[hexapla](https://github.com/cclawton/hexapla)**: early evaluation harness for running repeatable model tests, scoring outputs, and producing comparable result matrices.

---

## AI for creatives

I use AI and automation to help people inspect, transform, and finish work they already care about. The source material and creative decisions remain human. [Bullpen](https://github.com/cclawton/bullpen) covers the writing side; these projects cover music.

- **[asian-sentry-techniques](https://github.com/cclawton/asian-sentry-techniques)**: orchestration and composition notes from working in Logic Pro with foundation models. AI as co-composer, not autocomplete.
- **[music21-mcp](https://github.com/cclawton/music21-mcp)**: symbolic MIDI analysis and editing operations exposed through MCP, built on music21. It supports key and chord analysis, transposition, quantization, melody extraction, structural heuristics, and basic harmonization.
- **[preset-semantic](https://github.com/cclawton/preset-semantic)**: local-first semantic search for music-production presets across Helix, Arturia, and Decent Sampler. It turns musical descriptions into loadable preset candidates through a CLI or MCP tool.
- **[reascript-mcp](https://github.com/cclawton/reascript-mcp)**: tools for reading REAPER project state and generating Lua ReaScripts for actions that can be checked inside REAPER.

---

## Small tools

I also build local-first utilities for narrow problems. **[dv-joiner](https://github.com/cclawton/dv-joiner)** sorts timestamped DV clips and creates grouped, deinterlaced H.264/AAC access copies with FFmpeg. The original DV files remain the preservation masters.

---

## Writing

I write about AI deployment in Australian regulated sectors, sovereign infrastructure, and building with agents at [craiglawton.com](https://craiglawton.com). I am AWS-affiliated; the writing is personal.

---

## Connect

- Blog: [craiglawton.com](https://craiglawton.com)
- LinkedIn: [linkedin.com/in/craiglawton](https://linkedin.com/in/craiglawton)
- Podcast: [Building a Better Geek](https://buildingabettergeek.com)
