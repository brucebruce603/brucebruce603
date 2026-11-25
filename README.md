## Hi there 👋

Technician moving into AI evaluation. For 21 years I've built, inspected and verified complex systems against engineering standards, from submarine repair at two naval shipyards to now, and still having fun, liquid-metal systems for fusion & fission energy R&D. Today I use AI coding agents almost daily, and I focus on the question that matters most: is the agent's work actually right :?

Open source
claude-cowork-linux, pull request #206 (merged) A new app release refused local sessions on Linux. I traced it, working with Claude Code, to a file-system wrapper that dropped fs.realpath.native. The fix includes a regression test that fails without it, and I confirmed a security setting that disables local sessions was still enforced.
Issue #128 Reported a launch crash on Bazzite with versions, logs and a narrowed root cause, then verified the maintainer's fix on my own system.
Projects
Self-hosted LLM stack on Bazzite Linux: Ollama, Open WebUI, Whisper, Kokoro and ComfyUI in rootless Podman, with RAG over ChromaDB and hybrid search.
ReceiptScanner: an Android app (Kotlin) that reads receipts with the Gemini Vision API and feeds a Google Apps Script and Sheets backend. Built by directing Claude Code; I wrote the requirements and tested it on a physical device.
Publication

Co-author, "Century: Zap Energy's 100-kW-Scale Repetitive Sheared-Flow-Stabilized Z-Pinch System with Liquid Metal Cooling," Fusion Science and Technology 82(1–2), 2026. doi:10.1080/15361055.2025.2532331

## Now

- Learning Python by writing it myself, without AI help
- Building sample evaluation tasks for coding agents
