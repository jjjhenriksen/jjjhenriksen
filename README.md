# Hi, I’m Jacqueline 👋

**Data Science ’28 @ Chapman University · Break Through Tech AI Fellow · Community Staff @ [OpenClaw](https://github.com/openclaw)**

I keep coming back to the same question: how can we make complex AI systems easier for people to understand, trust, and use?

My work sits at the intersection of human–AI interaction, HCI, accessibility, and developer experience. I build tools that make evidence, system state, and privacy boundaries visible instead of asking people to treat AI as a black box.

## ✨ Featured work

The common thread across these projects is building trustworthy AI systems and accessible interfaces that help people work with complex technical material and workflows.

### 📐 [Interactive Proof](https://github.com/jjjhenriksen/interactive-proof)

An educational reading companion connecting mathematical papers, Lean formalizations, and focused AI explanations.

Readers can select a sentence, equation, or Lean declaration and request an explanation without losing their place in the proof. The interface keeps four kinds of evidence distinct:

- What the paper states
- What Lean formally verifies
- Relevant prerequisite knowledge
- What the AI generates

**Built with:** TypeScript, Next.js, Lean 4, PDF.js, Playwright, and the OpenAI Responses API

> 🚧 Tested release candidate; preparing the first public release.

### 🚀 [Artemis Lost](https://github.com/jjjhenriksen/Artemis-Lost)

🏆 **Entertainment Track Runner-Up — [PantherHacks 2026](https://pantherhacks.dev/winners)**

A full-stack science-fiction mission simulator where human players and AI-controlled crew members coordinate under pressure.

An AI mission director responds to player decisions while the application maintains structured world state, crew dynamics, tactical handoffs, mission mechanics, and persistent save data.

**Built with:** React, Vite, Node.js, Express, PostgreSQL, the OpenAI Responses API, and the Anthropic Messages API

### 🐾 [OpenClaw Pet](https://github.com/jjjhenriksen/openclaw-pet)

A cross-platform OpenClaw plugin that represents local and remote agent activity as animated desktop pets.

The plugin uses native overlays on macOS and Windows while enforcing a strict privacy boundary: prompts, credentials, tool arguments, model output, and internal errors never cross the display bridge.

**Built with:** TypeScript, Swift, C#, WebView2, and OpenClaw

## 🧪 Next projects

These projects extend the same interests into scientific computing, formalization tooling, and developer experience.

### ⚛️ [2D Hartree–Fock Lab](https://github.com/jjjhenriksen/hf2d-lab)

A serverless scientific workbench for restricted and unrestricted Hartree–Fock Born–Oppenheimer molecular dynamics in a model two-dimensional universe. It pairs a float64 Rust/WASM reference path with a TypeScript diagnostic implementation and an optional WebGPU backend, while making convergence, precision, and rejected unconverged steps visible in the interface.

**Built with:** TypeScript, Rust, WebAssembly, WebGPU, FFT convolution, and browser workers

### 🦀 [Lean 4 Codex Skills](https://github.com/jjjhenriksen/lean4-codex-skills)

A focused skill pack for LLM-assisted theorem proving and autoformalization: mentoring, mathematical exploration, declaration drafting, proof repair, review, build-checked checkpoints, and toolchain diagnosis.

**Built with:** Lean 4, Codex skills, Mathlib workflows, and proof-state-aware agent instructions

### 🧭 [Codex Native Selector](https://github.com/jjjhenriksen/codex-native-selector)

A Windows customization that turns Codex Desktop’s compact model selector into a clearer native interface with model-family tabs, reasoning controls, dynamic catalog discovery, Fast mode, and a portable-copy workflow that leaves the official installation untouched.

**Built with:** JavaScript, Electron ASAR tooling, PowerShell, Windows, and targeted bundle patching

### 🧩 [ClawHub Skill Pack](https://github.com/jjjhenriksen/agent-skills)

Published OpenClaw skills for reflection weaving, ambient signal capture, strategic reading, evidence-first review, and citation provenance. The pack treats agent behavior as a design surface: each skill narrows the task, preserves source boundaries, and makes quality checks explicit.

## 🦞 Open-source contributions

As an independent open-source contributor, I focus on developer experience, safer content workflows, and interfaces that adapt to how people actually work.

### [ClickClack](https://github.com/openclaw/clickclack)

- Made uploaded work usable without leaving the conversation through [safe previews for code, documents, PDFs, and HTML](https://github.com/openclaw/clickclack/pull/49), followed by [bounded spreadsheet and slide-deck previews](https://github.com/openclaw/clickclack/pull/55).
- Improved navigation and accessibility with [independently collapsible sidebar sections](https://github.com/openclaw/clickclack/pull/50) and [pointer, keyboard, and touch controls for channel ordering](https://github.com/openclaw/clickclack/pull/51).
- Let people shape the conversation layout around their preferences with [independent alignment controls for their own and others’ messages](https://github.com/openclaw/clickclack/pull/60).
- Added [matched search context](https://github.com/openclaw/clickclack/pull/81) and [search results in a sidebar](https://github.com/openclaw/clickclack/pull/83).
- Added [responsive Markdown tables](https://github.com/openclaw/clickclack/pull/93), [message reactions](https://github.com/openclaw/clickclack/pull/98), and [message editing](https://github.com/openclaw/clickclack/pull/99).
- Added [channel mention notifications](https://github.com/openclaw/clickclack/pull/116) and [pinned messages](https://github.com/openclaw/clickclack/pull/117).
- Fixed [right-aligned Markdown rendering](https://github.com/openclaw/clickclack/pull/135).
- Added [resolved mention highlighting](https://github.com/openclaw/clickclack/pull/137) and [named responding-agent status across channels and threads](https://github.com/openclaw/clickclack/pull/138).

### [OpenClaw](https://github.com/openclaw/openclaw)

- Restored reliable [end-to-end media delivery for ClickClack](https://github.com/openclaw/openclaw/pull/105775), made retries safe against duplicate messages, and removed a hard-coded model limit so replies follow the selected runtime and model budget.
- Added opt-in [ClickClack group-reply mention gating](https://github.com/openclaw/openclaw/pull/115484), preserving direct-message behavior while preventing ordinary group traffic from activating every account.
- Preserved original [cron timeout and cancellation reasons](https://github.com/openclaw/openclaw/pull/116566) through prompt handoff and finalization so operators can diagnose failed runs accurately.
- Fixed [restart recovery for deleted or unconfigured agent stores](https://github.com/openclaw/openclaw/pull/118023) while keeping configured custom stores eligible.

### [Lossless Claw](https://github.com/Martian-Engineering/lossless-claw)

- Fixed [delegated expansion reply collection](https://github.com/Martian-Engineering/lossless-claw/pull/1061) for current OpenClaw beta releases by using the supported session-message API and adding regression coverage.

## 🔬 Research interests

- **Human–AI interaction and HCI:** How interface design shapes people’s ability to understand, direct, and critically evaluate AI systems
- **Trustworthy AI and evidence:** Provenance, verification, evaluation, and clear boundaries between source material and model-generated output
- **Formalization and mechanized reasoning:** Translating informal mathematical arguments into precise, verifiable formal representations and studying the relationship between prose and proof
- **AI for mathematical and technical learning:** Connecting informal explanation, formal verification, and primary-source evidence

## 🛠️ Engineering interests

- **Accessible interfaces for technical work:** Reducing cognitive and interaction barriers in tools for complex documents, systems, and workflows
- **Developer experience for agent systems:** Making agent behavior more observable, controllable, and useful within real workflows
- **Reliable AI application architecture:** Designing explicit state, bounded data flows, privacy boundaries, and failure behavior into AI-powered products

## 🧰 Tools and technologies

- **Human-centered product engineering:** TypeScript, React, Next.js, accessible interaction design, and Playwright
- **AI systems and orchestration:** OpenAI Responses API, Anthropic Messages API, structured state, and agent workflows
- **Backend and persistence:** Node.js, Express, PostgreSQL, and bounded API contracts
- **Native and cross-platform interfaces:** Swift, C#/.NET, and WebView2
- **Formal methods and technical documents:** Lean 4, PDF.js, and evidence-aware interface design
- **Engineering practice:** automated testing, CI, privacy and security boundaries, Git, and GitHub

## 🌱 Currently

- Building Interactive Proof toward its first public release
- Developing 2D Hartree–Fock Lab as a browser-based numerical methods workbench
- Exploring LLM-assisted formalization through Lean 4 Codex Skills
- Studying Data Science at Chapman University
- Participating in the Break Through Tech AI program
- Building and contributing to open-source AI tooling

## 📫 Connect with me

- [LinkedIn](https://www.linkedin.com/in/jacqueline-henriksen/)
- [X](https://x.com/jjjhenriksen)
- [jjjhenriksen@gmail.com](mailto:jjjhenriksen@gmail.com)
