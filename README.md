# Craig Lawton

I build agentic systems, evaluate foundation models for Australian operating contexts, and make tools for creative work. The common thread is bounded systems, evidence, and keeping people in control.

---

## Agentic systems

Headless autonomous loops run on a Mac mini, with workers that produce, a supervisor that triages, and Signal for delivery. No dashboards or polling.

- **[supervisor](https://github.com/cclawton/supervisor)**: two-layer producer and verifier architecture. Workers write run files; a separate triage agent classifies them and signals only when something matters. It can integrate with any tool that writes to the filesystem, including Obsidian, CI, scrapers, and task managers.
- **[bullpen](https://github.com/cclawton/bullpen)**: profile-driven writing pipeline with bounded OpenCode stages, role-specific model routing, structural validation, and rollback on rejection. Optional Claude Code agents support a more flexible interactive workflow. The human editor controls publication.
- **[podcast-transcribe-exec-brief](https://github.com/cclawton/podcast-transcribe-exec-brief)**: polls podcast feeds, transcribes episodes locally with faster-whisper, and writes exec briefs into an Obsidian vault. There is no database; note frontmatter is the state store.
- **[podcastindex-mcp-server](https://github.com/cclawton/podcastindex-mcp-server)**: Podcast Index search, episode lookup, and feed discovery exposed as MCP tools.

---

## Keeping models honest

Leaderboards are a starting point. I am interested in repeatable tests tied to local tasks, constraints, cost, and evidence.

- **[hexapla](https://github.com/cclawton/hexapla)**: early evaluation harness for running repeatable model tests, scoring outputs, and producing comparable result matrices.
- **[react-harness](https://github.com/cclawton/react-harness)**: instrumented ReAct loop for comparing LLM coding agents on multi-file tasks, measuring success, tool-call efficiency, error recovery, and dollar cost. Includes a small GLM-5.2 vs Claude Opus 4.8 run, with caveats stated.
- **[voxtral-bedrock-sydney](https://github.com/cclawton/voxtral-bedrock-sydney)**: local web app demoing Mistral Voxtral on AWS Bedrock in ap-southeast-2, covering transcription, audio Q&A, summarisation, and translation with data kept in Australia.

---

## AI for creatives

I use AI and automation to help people inspect, transform, and finish work they already care about. The source material and creative decisions remain human. [Bullpen](https://github.com/cclawton/bullpen) covers the writing side; these projects cover music.

- **[asian-sentry-techniques](https://github.com/cclawton/asian-sentry-techniques)**: orchestration and composition notes from working in Logic Pro with foundation models. AI as co-composer, not autocomplete.
- **[music21-mcp](https://github.com/cclawton/music21-mcp)**: symbolic MIDI analysis and editing operations exposed through MCP, built on music21. It supports key and chord analysis, transposition, quantization, melody extraction, structural heuristics, and basic harmonization.
- **[preset-semantic](https://github.com/cclawton/preset-semantic)**: local-first semantic search for music-production presets across Helix, Arturia, and Decent Sampler. It turns musical descriptions into loadable preset candidates through a CLI or MCP tool.
- **[reascript-mcp](https://github.com/cclawton/reascript-mcp)**: tools for reading REAPER project state and generating Lua ReaScripts for actions that can be checked inside REAPER.

---

## Community and small tools

Local-first utilities for narrow problems, and software for the clubs and people around me.

- **[opencourt-display](https://github.com/cclawton/opencourt-display)**: open-source Raspberry Pi signage for sports clubs: court allocations, honours boards, and notices on clubhouse TVs. Volunteers keep using Google Slides or uploaded images. Started at a Melbourne tennis club; club specifics stay configurable and private.
- **[dv-joiner](https://github.com/cclawton/dv-joiner)**: sorts timestamped DV clips and creates grouped, deinterlaced H.264/AAC access copies with FFmpeg. The original DV files remain the preservation masters.
- **[simple-redact-video-tool](https://github.com/cclawton/simple-redact-video-tool)**: local web app for blurring or blacking out regions of video clips, rendered with FFmpeg.
- **[rain-cast](https://github.com/cclawton/rain-cast)**: Android rain prediction for Australia using Bureau of Meteorology data.
- **[simple-guitar-tuner](https://github.com/cclawton/simple-guitar-tuner)**: Android instrument tuner built with AI-assisted development.

---

## AWS samples

Sample code I built in my role at AWS. These are reference implementations, not production systems, and the views here remain my own.

- **[sample-agentcore-delphi](https://github.com/aws-samples/sample-agentcore-delphi)**: learned cross-model router on Amazon Bedrock AgentCore Runtime. It picks a foundation model per request across families such as Nova, Llama, Gemma and Claude, and ships a test harness that checks whether routing beats a single model on quality and cost, and reports when it does not.
- **[sample-kiro-enterprise-governance](https://github.com/aws-samples/sample-kiro-enterprise-governance)**: a Kiro Power for enterprise compliance workflows: standards enforcement through Bedrock Knowledge Bases, DOCX/PDF to markdown and back for spec-driven development, and a jurisdiction-agnostic AI assurance walkthrough.

---

## Writing

I write about AI deployment in Australian regulated sectors, sovereign infrastructure, and building with agents at [craiglawton.com](https://craiglawton.com). I am AWS-affiliated; the writing is personal.

---

## Connect

- Blog: [craiglawton.com](https://craiglawton.com)
- LinkedIn: [linkedin.com/in/craiglawton](https://linkedin.com/in/craiglawton)
- Podcast: [Building a Better Geek](https://buildingabettergeek.com)
