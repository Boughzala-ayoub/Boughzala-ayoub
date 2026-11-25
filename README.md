### Ayoub Boughzala

**Technical Leader & Senior Software Engineer** · Java · TypeScript / React · Rust · Python · AI Developer Tooling

5+ years building **STM32CubeMX** (STMicroelectronics' configuration and code-generation tool for STM32 microcontrollers) within a 50-engineer Agile program — driving the Java 8 → 21 modernization, owning core features end-to-end, and evolving headless/agentic CLI workflows. Outside work, I design and build AI coding-agent infrastructure (MCP servers, DAP debuggers, multi-agent workspaces), backend tooling, and native Windows systems apps.

Based in Tunisia · Open to relocation in Europe & remote roles.

[Portfolio](https://ayoubboughzala.netlify.app) · [LinkedIn](https://www.linkedin.com/in/ayoub-boughzala-8792b9200/) · [Email](mailto:ayoubboughzalaprep23@gmail.com)

---

#### Selected Open-Source Projects

**AI Agent Infrastructure & MCP Tooling**

| Project | Stack | Highlights |
|---|---|---|
| [**Loom**](https://github.com/Boughzala-ayoub/loom) | TypeScript · Rust / Tauri v2 · ConPTY | Thread-driven multi-agent terminal workspace running Claude, Codex, OpenCode, Cursor & Grok in isolated Git worktrees with OSC state tracking & Tailscale phone companion |
| [**aidebug**](https://github.com/Boughzala-ayoub/aidebug) | Python · DAP · Puppeteer | Multi-language runtime debugger (Python, JS/TS Node & Browser, Rust) with a deterministic JSON CLI, persistent adapter daemon & live Session Viewer with replay |
| [**earmcp**](https://github.com/Boughzala-ayoub/earmcp) | Python · PyTorch · Whisper · MCP | Local multimodal audio MCP server: 527-class AudioSet tagging, timestamped Whisper ASR, librosa DSP metrics & mel spectrograms |
| [**agentlink**](https://github.com/Boughzala-ayoub/agentlink) | Go · SQLite WAL · MCP | Daemonless cross-agent local MCP messaging bridge letting Claude, Codex, Cursor & OpenCode delegate tasks directly |
| [**Turbocharger (`tc`)**](https://github.com/Boughzala-ayoub/turbocharger) | Rust · Tree-sitter · stdio MCP | Offline AST code-zoom (TS/JS, Python, Rust, Java) and installed dependency signature lookups with token-savings telemetry |
| [**agentdbg**](https://github.com/Boughzala-ayoub/agentdbg) | Python stdlib (zero deps) | Synchronous `PreToolUse` breakpoint debugger for Claude Code — pause, inspect, edit, or deny tool calls with fail-open safety |
| [**traceprobe**](https://github.com/Boughzala-ayoub/traceprobe) | Go (zero deps) | Single-binary loopback HTTP probe collector giving coding agents live runtime values via CLI |

**Backend, Web & Native Systems**

| Project | Stack | Highlights |
|---|---|---|
| [**GitGate**](https://github.com/Boughzala-ayoub/gitgate) | Java 21 · Spring Boot · JGit · React | Self-hostable Git server enforcing server-side per-user path-level read/write ACLs by deterministically rewriting branch history per read scope |
| [**Sprout**](https://github.com/Boughzala-ayoub/sprout) | Java · WasmGC · TeaVM | React-style, Spring-flavored Java UI framework compiling to browser WasmGC with keyed VDOM reconciliation, build-time DI & Maven archetype |
| [**Wisp**](https://github.com/Boughzala-ayoub/wisp) | Rust · libghostty-vt · Direct3D 11 · ConPTY | Native Windows GPU-accelerated terminal emulator with tabs, splits, ligatures, acrylic/Mica & 771 Ghostty themes |
| [**Screenshot Studio**](https://github.com/Boughzala-ayoub/screenshot-studio) | Rust · Tauri v2 · TypeScript · Win32/OLE | Native Windows cross-monitor capture, 8-tool Canvas 2D markup & redaction editor, H.264/MP4 region recorder, dual floating pins & COM/OLE drag-out |
| [**AI Usage Overlay**](https://github.com/Boughzala-ayoub/ai-usage-overlay) | Electron · JavaScript · Puppeteer | Transparent, click-through multi-monitor Windows HUD & Android companion showing polled usage quotas, reset countdowns & rate-limit backoff |
| [**cubemx-tools**](https://github.com/Boughzala-ayoub/cubemx-tools) & [**mxBroker**](https://github.com/Boughzala-ayoub/mxBroker) | Java · Python · MCP | Headless STM32CubeMX CLI & MCP server with set-aware three-way `.ioc` merging (`.cube`) + warm-session daemon |
| [**iar2cmake**](https://github.com/Boughzala-ayoub/iar2cmake) | TypeScript | Converter turning IAR EWARM STM32 projects into CMake/ARM-GCC with CubeMX-style presets |

---

#### Core Stack

- **Languages:** Java (8 → 21), TypeScript, JavaScript, Python, Rust, Go, SQL
- **AI & Developer Tooling:** Model Context Protocol (MCP), Debug Adapter Protocol (DAP), Tree-sitter, PyTorch, Hugging Face Transformers, Whisper, Librosa
- **Frontend & Desktop:** React, Angular, Java Swing, Tauri 2, Electron, Win32/COM/OLE, Direct3D 11, Canvas 2D, WebAssembly (WasmGC)
- **Backend & Systems:** Spring Boot, JGit, Node.js, REST APIs, SQLite (WAL, FTS5), ConPTY, Git, Gerrit, Jenkins CI, JUnit, Puppeteer
