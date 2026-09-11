# Hi, I’m Jacqueline 👋

**Data Science ’28 @ Chapman University · Break Through Tech AI Fellow · Community Staff @ [OpenClaw](https://github.com/openclaw)**

I build human-centered AI products, developer tools, and research interfaces that make complex systems easier to understand, direct, and trust.

My work sits at the intersection of HCI, accessibility, developer experience, reliable agent systems, formal methods, and scientific computing. I care about making evidence, system state, privacy boundaries, and failure behavior visible to the people using AI.

## 🚀 Featured work

### [Interactive Proof](https://github.com/jjjhenriksen/interactive-proof)

An educational reading companion for mathematical papers, Lean formalizations, and grounded AI explanations. Readers can select a sentence, equation, or Lean declaration and ask for help without losing their place in the proof.

The interface keeps four kinds of evidence distinct: what the paper states, what Lean formally verifies, prerequisite knowledge, and what the AI generates.

**Built with:** TypeScript, Next.js, Lean 4, PDF.js, Playwright, and the OpenAI Responses API  
[Try the live demo](https://interactive-proof.jjjhenriksen.chatgpt.site)

### [OpenClaw Pet](https://github.com/jjjhenriksen/openclaw-pet)

A cross-platform OpenClaw plugin that represents local and remote agent activity as animated desktop pets. Native overlays on macOS and Windows show allowlisted activity state while keeping prompts, credentials, tool arguments, model output, and internal errors off the display bridge.

**Built with:** TypeScript, Swift, C#/.NET, WebView2, and OpenClaw

### [The Shape-Note Atlas](https://github.com/jjjhenriksen/shapenote-atlas)

A source-faithful Sacred Harp lookup workspace spanning eleven books and thousands of tune records. It combines corpus metadata, edition-specific source evidence, MusicXML scores, browser playback, transposition, and human-review queues without fabricating missing notation.

[Open the Atlas](https://shapenote.jacquelinehenriksen.com/atlas/)

### [Hollow Square](https://github.com/jjjhenriksen/hollow-square)

A small browser-playable Sacred Harp horror game about song, memory, and the class that remains. It is a dependency-light static project with story, shape-note practice, short tune openings, optional four-part harmony, and original artwork.

[Play Hollow Square](https://shapenote.jacquelinehenriksen.com/hollow-square/)

### [Artemis Lost](https://github.com/jjjhenriksen/Artemis-Lost)

🏆 **Entertainment Track Runner-Up — [PantherHacks 2026](https://pantherhacks.dev/winners)**

A full-stack science-fiction mission simulator where human players and AI-controlled crew coordinate under pressure. An AI mission director responds to player decisions while the application maintains structured world state, crew dynamics, tactical handoffs, mission mechanics, and persistent saves.

**Built with:** React, Vite, Node.js, Express, PostgreSQL, the OpenAI Responses API, and the Anthropic Messages API

## 🧩 Research, tools, and supporting projects

- **[2D Hartree–Fock Lab](https://github.com/jjjhenriksen/hf2d-lab):** A serverless, browser-based numerical methods workbench for real-space molecular dynamics, with visible convergence and precision behavior. [Open the lab](https://jacquelinehenriksen.com/hf2d-lab/)
- **[Sacred Harp Llama Fine-tune](https://github.com/jjjhenriksen/sacred-harp-finetune):** A reproducible Apple Silicon LoRA training and evaluation pipeline for a small Sacred Harp reference model, paired with grounded retrieval and a public presentation. [View the presentation](https://jjjhenriksen.github.io/sacred-harp-finetune/)
- **[Shape-Note site](https://github.com/jjjhenriksen/shapenote-site):** A publication hub connecting the Atlas, Local AI work, and Hollow Square.
- **[Lean 4 Codex Skills](https://github.com/jjjhenriksen/lean4-codex-skills):** Agent skills for theorem proving, autoformalization, proof repair, review, build-checked checkpoints, and toolchain diagnosis.
- **[ClawHub Skill Pack](https://github.com/jjjhenriksen/agent-skills):** Published OpenClaw skills for reflection weaving, strategic reading, evidence-first review, signal capture, and citation provenance.
- **[Chapman Connect](https://github.com/jjjhenriksen/HCI-Chapman-Connect):** A working HCI prototype for connecting Chapman students with campus resources.

## 🦞 Open-source contributions

As an independent open-source contributor, I focus on developer experience, safer content workflows, reliable agent systems, and interfaces that adapt to how people actually work.

### [OpenClaw](https://github.com/openclaw/openclaw)

Recent merged work includes:

- [Skill Workshop review-index repair](https://github.com/openclaw/openclaw/pull/142522), keeping durable review state consistent after updates
- [Agent automation editing from Settings](https://github.com/openclaw/openclaw/pull/139782)
- [Primary-user identity in the multi-agent profile hero](https://github.com/openclaw/openclaw/pull/136736)
- [Native compaction serialization](https://github.com/openclaw/openclaw/pull/135441) and [restored subagent requester-settle recovery](https://github.com/openclaw/openclaw/pull/133057)
- [Embedding-only managed-server support](https://github.com/openclaw/openclaw/pull/125383), [explicit system-agent configuration](https://github.com/openclaw/openclaw/pull/125377), and [inherited skill-allowlist visibility](https://github.com/openclaw/openclaw/pull/124429)
- [Queued-message editing](https://github.com/openclaw/openclaw/pull/124298), [catalog-timeout classification](https://github.com/openclaw/openclaw/pull/124288), and [agent-owned multi-agent CLI operations](https://github.com/openclaw/openclaw/pull/123871)
- [Bot-to-bot inbound dispatch](https://github.com/openclaw/openclaw/pull/119278), [restart recovery for deleted or unconfigured agent stores](https://github.com/openclaw/openclaw/pull/118023), [native ClickClack progress](https://github.com/openclaw/openclaw/pull/116683), [cron-reason preservation](https://github.com/openclaw/openclaw/pull/116566), [mention gating](https://github.com/openclaw/openclaw/pull/115484), and [ClickClack media delivery](https://github.com/openclaw/openclaw/pull/105775)

Current open work includes [release-safe compaction cleanup](https://github.com/openclaw/openclaw/pull/144511), [LaTeX rendering in Control UI Markdown](https://github.com/openclaw/openclaw/pull/144324), [dashboard child-session pinning](https://github.com/openclaw/openclaw/pull/143719), [deleted-archive retention](https://github.com/openclaw/openclaw/pull/140793), [native plugin stylesheet loading on macOS](https://github.com/openclaw/openclaw/pull/139735), [saved gateway-account switching](https://github.com/openclaw/openclaw/pull/136687), and [automation grouping and tags](https://github.com/openclaw/openclaw/pull/134434).

### [ClickClack](https://github.com/openclaw/clickclack)

- Made uploaded work usable without leaving the conversation through [safe previews for code, documents, PDFs, and HTML](https://github.com/openclaw/clickclack/pull/49), followed by [bounded spreadsheet and slide-deck previews](https://github.com/openclaw/clickclack/pull/55).
- Improved navigation and accessibility with [collapsible sidebar sections](https://github.com/openclaw/clickclack/pull/50), [draggable channel ordering](https://github.com/openclaw/clickclack/pull/51), and [independent message alignment controls](https://github.com/openclaw/clickclack/pull/60).
- Added [matched search context](https://github.com/openclaw/clickclack/pull/81), [sidebar search results](https://github.com/openclaw/clickclack/pull/83), [responsive Markdown tables](https://github.com/openclaw/clickclack/pull/93), [message reactions](https://github.com/openclaw/clickclack/pull/98), and [message editing](https://github.com/openclaw/clickclack/pull/99).
- Added [channel mention notifications](https://github.com/openclaw/clickclack/pull/116), [pinned messages](https://github.com/openclaw/clickclack/pull/117), [resolved mention highlighting](https://github.com/openclaw/clickclack/pull/137), and [named responding-agent status](https://github.com/openclaw/clickclack/pull/138).

### [Lossless Claw](https://github.com/Martian-Engineering/lossless-claw)

- Fixed [delegated expansion reply collection](https://github.com/Martian-Engineering/lossless-claw/pull/1061) for current OpenClaw beta releases using the supported session-message API, with regression coverage.

## 🔬 Focus areas and tools

- **Human-centered AI:** HCI, accessibility, evidence-aware interfaces, and AI for technical learning
- **Agent systems:** Observable workflows, bounded data flows, privacy boundaries, and failure behavior
- **Formal and scientific computing:** Lean 4, mechanized reasoning, numerical methods, and browser-based research tools
- **Stack:** TypeScript, React, Next.js, Node.js, PostgreSQL, Playwright, Swift, C#/.NET, Python, Rust/WASM, OpenAI and Anthropic APIs

## 🌱 Currently

- Extending the Shape-Note Atlas and its source-grounded review workflow
- Developing OpenClaw Pet as a privacy-preserving activity interface
- Building 2D Hartree–Fock Lab as a browser-based numerical methods workbench
- Creating reusable skills for agent workflows, theorem proving, and evidence-first knowledge work
- Studying Data Science at Chapman University and participating in Break Through Tech AI
- Building and contributing to open-source AI tooling

## 📫 Connect with me

- [Website](https://jacquelinehenriksen.com/)
- [LinkedIn](https://www.linkedin.com/in/jacqueline-henriksen/)
- [X](https://x.com/jjjhenriksen)
- [jjjhenriksen@gmail.com](mailto:jjjhenriksen@gmail.com)
