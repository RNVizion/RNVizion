# Hey, I’m Christian Smith (RNVizion) ⚡

I build production AI systems on the Claude API — RAG, LLM agents, a published MCP server, and an Apache-2.0 agent-identity layer — plus polished developer tools that actually feel good to use.
By day I work in AR/XR sales and support at Meta. Outside of that I’m a game developer, creative technologist, writer, and relentless tinkerer.

I care about the gap between software that *works* and software that *feels right* — clean architecture, thoughtful UX, and the kind of engineering notes that explain *why*, not just *what*. Lately I write about keeping that same care when AI lets you build ten times faster, over at [rnvizion.dev](https://rnvizion.dev).

-----

## 🤖 AI Systems & MCP

Building on top of large language models: grounded, guardrailed, and deterministic where it counts.

|Project                                                                          |Description                                                                                                                                          |
|---------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
|[**AIII — AI Identification Initiative**](https://rnvizion.dev/aiii)              |Apache-2.0 reference implementation ([rnv-mcp-identity](https://github.com/RNVizion/rnv-mcp-identity)) for AI agent identity — an L1–L3 identity-and-authorization layer for MCP servers; resolves or refuses, never guesses. 46 tests, property-based eval gates, runnable FastMCP demo. Sigstore-signed releases, CycloneDX SBOM, OpenSSF Baseline at 20 of 21 controls|
|[**Ask the Corpus**](https://huggingface.co/spaces/RNVizion/ask-the-corpus)      |Retrieval-augmented (RAG) assistant over my published writing — sentence-transformers + ChromaDB, grounded through Claude with citations, rate-limited and cost-guarded. Refusal is enforced, not hoped for: a CI eval suite fails the build if retrieval slips, if it stops refusing what it can’t answer, or if it starts refusing what it can. Live on Hugging Face|
|[**RNV Publishing Agent**](https://github.com/RNVizion/rnv-publishing-agent)      |FastMCP server with a Claude agent loop that automates a content-publishing workflow — validates a post’s metadata, generates its card and OG image, commits and pushes, then updates the corpus behind Ask the Corpus. Refuses to publish anything that fails validation|
|[**rnv-color-mcp**](https://github.com/RNVizion/rnv-color-mcp)                    |Color-computation server on the Model Context Protocol, published to the official MCP registry and listed in awesome-mcp-servers. Nine deterministic tools (conversion, harmony, mixing, WCAG contrast, CIEDE2000); the model decides intent, the tool owns the exact value — resolves or refuses, never guesses. Also an OAuth 2.1 resource server: RFC 9728 protected-resource metadata, enforced per-tool scopes|

-----

## 🧰 The RNVizion Toolkit

A suite of five professional desktop applications built with PyQt6. Each ships with full CLI support, cross-platform CI, and three theme modes (Dark / Light / Image).

|App                                                                                   |Description                                                                                                                   |
|--------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|
|[**RNV Text Transformer**](https://github.com/RNVizion/rnv-text-transformer)          |11 transformation modes, 9+ file formats, regex builder, folder watching, compare view — backed by 786 tests and ~76% coverage|
|[**RNV Color Palette Manager**](https://github.com/RNVizion/rnv-color-palette-manager)|Professional palette management with 16+ export formats, 7 mixing algorithms, and WCAG accessibility tools                    |
|[**RNV Color Picker**](https://github.com/RNVizion/rnv-color-picker)                  |Screen color extraction with magnifier, WCAG contrast checker, and color harmony generation                                   |
|[**RNV Icon Builder**](https://github.com/RNVizion/rnv-icon-builder)                  |Multi-resolution ICO creation from PNG/SVG/ICO sources with Android, iOS, and favicon export targets                          |
|[**RNV Color Mixer**](https://github.com/RNVizion/rnv-color-mixer)                    |Real-world paint mixing simulation in a digital palette, powered by Kubelka-Munk theory                                       |

-----

## 🛠 Tech Stack

**Languages**
`Python` · `C++` · `C#` · `Java` · `JavaScript` · `SQL` · `HTML`

**AI / ML**
`Claude API` · `RAG` · `ChromaDB` · `sentence-transformers` · `MCP / FastMCP` · `Gradio` · `Hugging Face`

**Security & Identity**
`OAuth 2.1` · `RFC 9728` · `holder-of-key (RFC 7800/7638)` · `per-tool scopes`

**Frameworks & Tools**
`PyQt6` · `Unity` · `Unreal Engine` · `Git` · `GitHub Actions` · `Docker`

**Creative & 3D**
`zBrush` · `3DS Max` · `Substance Painter` · `Adobe Creative Suite`

**Testing**
`pytest` · `pytest-qt` · `hypothesis` · `syrupy` · `coverage.py` · `CI-gated LLM evals`

-----

## 🎮 Background

- 🎓 BS in Game Programming and Development — Southern New Hampshire University
- 🥽 AR/XR Sales & Technical Support — Meta
- ✍️ Content Developer — built training materials, scripts, and educational media at Vitalyst
- 🧭 Exploring remote AI Engineer, Solutions Engineer, and Developer Advocate roles — where building, communicating, and shipping production systems all matter

-----

## 📫 Let’s Connect

[![Website](https://img.shields.io/badge/Website-rnvizion.dev-d2bc93?logo=firefox&logoColor=white)](https://rnvizion.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Christian%20Smith-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rnvizion/)

-----

*Building tools that developers actually want to use.*
