 ## 🧱 Rewriting Project Claw Code

<p align="center">
  <img src="https://i.imgur.com/J8Do1R1.jpeg" alt="Claw" width="350" />
</p>

<p align="center">
  <strong> Better harness tools, focused on execution not merely storing the archive of leaked Claude Code 

</strong>
</p>

---



## ⭐ Support

If you find this project useful, consider giving it a star ⭐ and following me on GitHub. If you need assistance DM me through my socials.
<p align="center">
  <a href="https://github.com/0xKarl-dev/claw-codes#-support-the-project">
    <img src="https://img.shields.io/badge/Sponsor-GitHub-ea4aaa?style=for-the-badge&logo=github" alt="Sponsor on GitHub" />
  </a>
</p>

---
## Star History
This repository started gaining traction shortly after I backed up the code within a few hours of discovery.

<a href="https://www.star-history.com/?repos=0xKarl-dev%2Fclaw-codes&type=date&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/image?repos=0xKarl-dev/claw-codes&type=date&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/image?repos=0xKarl-dev/claw-codes&type=date&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/image?repos=0xKarl-dev/claw-codes&type=date&legend=top-left" />
 </picture>
</a>

</p>
## 🏆 Featured

<p align="center">
  <a href="https://aidigitalcrew.com/project.html?repo=0xKarl-dev%2Fclaw-codes" target="_blank">
    <img src="https://img.shields.io/badge/🚀%20Featured%20on-AI%20Digital%20Crew-blue?style=for-the-badge&logo=github" />
  </a>
</p>

<p align="center">
  Claw Codes was selected as <strong>Project of the Day</strong> —  
  recognized for innovation in AI agent tooling.
</p>

<p align="center">
  <a href="https://aidigitalcrew.com/project.html?repo=0xKarl-dev%2Fclaw-codes" target="_blank">
    👉 View Full Feature
  </a>
</p>

>
> [!IMPORTANT]
> 🚧🦀 **Rust Port in Progress**
> Rust port is now in progress on the [`dev/rust`](https://github.com/0xKarl-dev/claw-codes/tree/dev/rust) branch and is being merged into main as we build it. The Rust implementation aims to deliver a faster, memory-safe harness runtime. I'm collaborating with a close contributor to accelerate development process.
> 
> Stay tuned — this will become the core direction of the project.


---

## 🔄 Current Direction

Claw Codes is not a finished product. It is a **system under active development**, with a focus on:
- 🦀 Rust-based core engine (in progress)  
- 🐍 Python orchestration layer  
- ⚙️ Improved execution pipeline  
- 🧩 Modular system architecture  
- 🔍 Continuous reverse engineering and refinement  
- 🧠 Exploration of agent-based system design  
Each part of the system is being designed with performance, clarity, and scalability in mind.

---

## 🧠 Vision

The goal of Claw Codes is to evolve into a foundation for:
- intelligent execution systems  
- autonomous workflows  
- agent-driven applications  
- modular AI tooling infrastructure  
Rather than focusing solely on generation, the system prioritizes:
> **Execution, control, and structured automation**

---


## Rust Port

The Rust workspace under `rust/` is the current systems-language port of the project.

It currently includes:

- `crates/api-client` — API client with provider abstraction, OAuth, and streaming support
- `crates/runtime` — session state, compaction, MCP orchestration, prompt construction
- `crates/tools` — tool manifest definitions and execution framework
- `crates/commands` — slash commands, skills discovery, and config inspection
- `crates/plugins` — plugin model, hook pipeline, and bundled plugins
- `crates/compat-harness` — compatibility layer for upstream editor integration
- `crates/claw-cli` — interactive REPL, markdown rendering, and project bootstrap/init flows

Run the Rust build:

```bash
cd rust
cargo build --release
```

## Backstory

Being written



---

## Porting Status

The main source tree is now Python-first.

- `src/` contains the active Python porting workspace
- `tests/` verifies the current Python workspace
- the exposed snapshot is no longer part of the tracked repository state

The current Python workspace is not yet a complete one-to-one replacement for the original system, but the primary implementation surface is now Python.

## Why this rewrite exists

I originally studied the exposed codebase to understand its harness, tool wiring, and agent workflow. After spending more time with the legal and ethical questions—and after reading the essay linked below—I did not want the exposed snapshot itself to remain the main tracked source tree.

This repository now focuses on Python porting work instead.

## Repository Layout

```text
.
├── src/                                # Python porting workspace
│   ├── __init__.py
│   ├── commands.py
│   ├── main.py
│   ├── models.py
│   ├── port_manifest.py
│   ├── query_engine.py
│   ├── task.py
│   └── tools.py
├── rust/                               # Rust port (claw CLI)
│   ├── crates/api/                     # API client + streaming
│   ├── crates/runtime/                 # Session, tools, MCP, config
│   ├── crates/claw-cli/               # Interactive CLI binary
│   ├── crates/plugins/                 # Plugin system
│   ├── crates/commands/                # Slash commands
│   ├── crates/server/                  # HTTP/SSE server (axum)
│   ├── crates/lsp/                    # LSP client integration
│   └── crates/tools/                   # Tool specs
├── tests/                              # Python verification
├── assets/omx/                         # OmX workflow screenshots
├── 2026-03-09-is-legal-the-same-as-legitimate-ai-reimplementation-and-the-erosion-of-copyleft.md
└── README.md
```

## Python Workspace Overview

The new Python `src/` tree currently provides:

- **`port_manifest.py`** — summarizes the current Python workspace structure
- **`models.py`** — dataclasses for subsystems, modules, and backlog state
- **`commands.py`** — Python-side command port metadata
- **`tools.py`** — Python-side tool port metadata
- **`query_engine.py`** — renders a Python porting summary from the active workspace
- **`main.py`** — a CLI entrypoint for manifest and summary output

## 💬 Support / Questions

For questions, discussions, or collaboration:

👉 Telegram: https://t.me/Carl_Crypt

Feel free to reach out if you’re interested in:

- the architecture  
- contributions  
- ideas and improvements  
- general discussions about AI systems 


## 💖 Support the Project

If you find this work useful, consider supporting **0xKarl-dev** to help continue open-source harness engineering research.

### 🪙 Wallets

**BTC**

```
bc1q0dhqj9e3fwnmjf78ns33xee0g0plveq4w8khga
```

**SOL**

```
Eers7E3yXFDRQFouTFGmbR5rLLX3teHxLVSBEinUhcD3
```

**EVM**

```
0x6D4688C4c41b5481ea76FA03F3857C8F002476be
```

<p align="center">
  <em>Click the address to easily copy</em>
</p>


---

## Quickstart

Render the Python porting summary:

```bash
python3 -m src.main summary
```

Print the current Python workspace manifest:

```bash
python3 -m src.main manifest
```

List the current Python modules:

```bash
python3 -m src.main subsystems --limit 16
```

Run verification:

```bash
python3 -m unittest discover -s tests -v
```

Run the parity audit against the local ignored archive (when present):

```bash
python3 -m src.main parity-audit
```

Inspect mirrored command/tool inventories:

```bash
python3 -m src.main commands --limit 10
python3 -m src.main tools --limit 10
```

## Current Parity Checkpoint

The port now mirrors the archived root-entry file surface, top-level subsystem names, and command/tool inventories much more closely than before. However, it is **not yet** a full runtime-equivalent replacement for the original TypeScript system; the Python tree still contains fewer executable runtime slices than the archived source.


## Star History

See the chart at the top of this README.

## Ownership / Affiliation Disclaimer

- This repository does **not** claim ownership of the original Claw Code source material.
- This repository is **not affiliated with, endorsed by, or maintained by the original authors**.



---

## 🤝 Contributing
Contributions are welcome.
Ways to contribute:
- Improve system architecture  
- Add new features  
- Optimize performance  
- Fix issues  
- Suggest improvements  
- Share ideas and feedback  

---

## 📦 Status

Claw Codes is currently:
- under active development  
- not yet stable  
- continuously evolving  
Expect frequent updates, restructuring, and improvements as the system matures.

---

## ⚠️ Disclaimer

Claw Codes is an independent, clean-room implementation and is **not affiliated with, endorsed by, or maintained by any organization or company referenced in this project**.

This repository is intended strictly for:
- Educational purposes  
- Software architecture exploration  
- Defensive and research-driven development  
- Experimental AI system design  

No proprietary claims are made over any external systems or codebases.

---


## 👤 Maintained By

**0xKarl:**  https://x.com/0xKarl  

--- 
