# Awesome Context AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of tools, frameworks, and resources for building AI applications with rich context from screen recordings, audio, activity tracking, and personal data.

The future of AI is **context-aware**. These tools help you build AI that understands what you've seen, heard, said, and done.

## Contents

- [Screen & Activity Recording](#screen--activity-recording)
- [Memory & Context Systems](#memory--context-systems)
- [AI Frameworks with Context Support](#ai-frameworks-with-context-support)
- [MCP Servers (Model Context Protocol)](#mcp-servers-model-context-protocol)
- [Personal Knowledge Management](#personal-knowledge-management)
- [OCR & Text Extraction](#ocr--text-extraction)
- [Audio Transcription](#audio-transcription)
- [Context for Coding](#context-for-coding)
- [Research & Papers](#research--papers)
- [Building with Context](#building-with-context)

## Screen & Activity Recording

Tools that capture your digital activity for AI-powered recall and search.

### Open Source

| Tool | Platform | Description | Stars |
|------|----------|-------------|-------|
| [Screenpipe](https://github.com/screenpipe/screenpipe) | macOS, Windows, Linux | 24/7 local screen & mic recording; indexes accessibility text, OCR, and transcripts for AI search and agents. Works with Ollama. | ![GitHub stars](https://img.shields.io/github/stars/screenpipe/screenpipe) |
| [Pensieve](https://github.com/arkohut/pensieve) | macOS, Windows, Linux | Passive screenshot recording with OCR and semantic search, runs fully local | ![GitHub stars](https://img.shields.io/github/stars/arkohut/pensieve) |
| [OpenRecall](https://github.com/openrecall/openrecall) | macOS, Windows, Linux | Privacy-first alternative to Windows Recall | ![GitHub stars](https://img.shields.io/github/stars/openrecall/openrecall) |
| [Windrecorder](https://github.com/yuka-friends/Windrecorder) | Windows | Memory search app with OCR and image description | ![GitHub stars](https://img.shields.io/github/stars/yuka-friends/Windrecorder) |
| [OpenRewind](https://github.com/alikia2x/openrewind) | macOS (Apple Silicon) | Open source Rewind alternative | ![GitHub stars](https://img.shields.io/github/stars/alikia2x/openrewind) |
| [OpenReLife](https://github.com/porech/openrelife) | Cross-platform | Fork of OpenRecall with UX focus | ![GitHub stars](https://img.shields.io/github/stars/porech/openrelife) |

### Commercial

| Tool | Description |
|------|-------------|
| [Limitless](https://www.limitless.ai/) | Personalized AI from everything you've seen, said, or heard. Formerly Rewind.ai; acquired by Meta (Dec 2025), with the Rewind desktop app being wound down |
| [Microsoft Recall](https://support.microsoft.com/en-us/windows/recall) | Windows feature that takes periodic snapshots for AI-powered search |

## Memory & Context Systems

Frameworks for adding persistent memory to AI agents.

| Tool | Description | Stars |
|------|-------------|-------|
| [Mem0](https://github.com/mem0ai/mem0) | Memory layer for AI agents with LangChain/LlamaIndex integration | ![GitHub stars](https://img.shields.io/github/stars/mem0ai/mem0) |
| [Letta](https://github.com/letta-ai/letta) | Stateful agents with long-term memory, the productized successor to MemGPT | ![GitHub stars](https://img.shields.io/github/stars/letta-ai/letta) |
| [Zep](https://github.com/getzep/zep) | Long-term memory for AI assistants | ![GitHub stars](https://img.shields.io/github/stars/getzep/zep) |
| [Graphiti](https://github.com/getzep/graphiti) | Real-time, temporally-aware knowledge graphs for agent memory | ![GitHub stars](https://img.shields.io/github/stars/getzep/graphiti) |
| [Cognee](https://github.com/topoteretes/cognee) | Memory and knowledge-graph layer for AI agents and RAG | ![GitHub stars](https://img.shields.io/github/stars/topoteretes/cognee) |
| [LangMem](https://github.com/langchain-ai/langmem) | Long-term memory for LangChain agents | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langmem) |

## AI Frameworks with Context Support

Major frameworks that support rich context and RAG.

| Framework | Context Features | Stars |
|-----------|-----------------|-------|
| [LangChain](https://github.com/langchain-ai/langchain) | Memory modules, retrievers, document loaders | ![GitHub stars](https://img.shields.io/github/stars/langchain-ai/langchain) |
| [LlamaIndex](https://github.com/run-llama/llama_index) | 300+ data connectors, knowledge graphs | ![GitHub stars](https://img.shields.io/github/stars/run-llama/llama_index) |
| [Haystack](https://github.com/deepset-ai/haystack) | Document stores, retrievers, pipelines | ![GitHub stars](https://img.shields.io/github/stars/deepset-ai/haystack) |
| [Semantic Kernel](https://github.com/microsoft/semantic-kernel) | Memory, planners, plugins | ![GitHub stars](https://img.shields.io/github/stars/microsoft/semantic-kernel) |
| [AutoGen](https://github.com/microsoft/autogen) | Multi-agent conversations with context | ![GitHub stars](https://img.shields.io/github/stars/microsoft/autogen) |

## MCP Servers (Model Context Protocol)

The [Model Context Protocol](https://modelcontextprotocol.io/) standardizes how AI models access external context.

### Official & Curated Lists

- [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) - Official MCP servers
- [wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) - Community curated list
- [appcypher/awesome-mcp-servers](https://github.com/appcypher/awesome-mcp-servers) - Another curated list

### Context-Relevant MCP Servers

| Server | Description |
|--------|-------------|
| [Memory](https://github.com/modelcontextprotocol/servers/tree/main/src/memory) | Knowledge graph-based persistent memory |
| [Filesystem](https://github.com/modelcontextprotocol/servers/tree/main/src/filesystem) | Secure local file operations |
| [Screenpipe MCP](https://github.com/screenpipe/screenpipe) | Access screen recordings and transcripts |
| [Browser](https://github.com/anthropics/anthropic-quickstarts/tree/main/computer-use-demo) | Browser automation and context |

## Personal Knowledge Management

Tools for organizing and querying personal knowledge.

| Tool | Description | Stars |
|------|-------------|-------|
| [Obsidian](https://obsidian.md/) | Knowledge base on local markdown files | N/A (closed) |
| [Logseq](https://github.com/logseq/logseq) | Privacy-first, open-source knowledge base | ![GitHub stars](https://img.shields.io/github/stars/logseq/logseq) |
| [SiYuan](https://github.com/siyuan-note/siyuan) | Privacy-first, local-first PKM with block-level editing | ![GitHub stars](https://img.shields.io/github/stars/siyuan-note/siyuan) |
| [Khoj](https://github.com/khoj-ai/khoj) | AI personal assistant for your digital brain | ![GitHub stars](https://img.shields.io/github/stars/khoj-ai/khoj) |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | All-in-one desktop app to chat with your docs, fully local option | ![GitHub stars](https://img.shields.io/github/stars/Mintplex-Labs/anything-llm) |
| [Quivr](https://github.com/QuivrHQ/quivr) | Your GenAI second brain | ![GitHub stars](https://img.shields.io/github/stars/QuivrHQ/quivr) |
| [PrivateGPT](https://github.com/zylon-ai/private-gpt) | Chat with your documents privately | ![GitHub stars](https://img.shields.io/github/stars/zylon-ai/private-gpt) |

## OCR & Text Extraction

Extract text from screens, documents, and images.

| Tool | Platform | Description | Stars |
|------|----------|-------------|-------|
| [Tesseract](https://github.com/tesseract-ocr/tesseract) | Cross-platform | The definitive open source OCR engine | ![GitHub stars](https://img.shields.io/github/stars/tesseract-ocr/tesseract) |
| [Surya](https://github.com/datalab-to/surya) | Cross-platform | Modern OCR with layout and reading-order detection in 90+ languages | ![GitHub stars](https://img.shields.io/github/stars/datalab-to/surya) |
| [Marker](https://github.com/datalab-to/marker) | Cross-platform | Convert PDFs and images to clean markdown/JSON | ![GitHub stars](https://img.shields.io/github/stars/datalab-to/marker) |
| [olmOCR](https://github.com/allenai/olmocr) | Cross-platform | Toolkit for converting PDFs and documents to text with VLMs | ![GitHub stars](https://img.shields.io/github/stars/allenai/olmocr) |
| [EasyOCR](https://github.com/JaidedAI/EasyOCR) | Cross-platform | Ready-to-use OCR with 80+ languages | ![GitHub stars](https://img.shields.io/github/stars/JaidedAI/EasyOCR) |
| [PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR) | Cross-platform | Multilingual OCR toolkit | ![GitHub stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleOCR) |
| [docTR](https://github.com/mindee/doctr) | Cross-platform | Document text recognition | ![GitHub stars](https://img.shields.io/github/stars/mindee/doctr) |
| Apple Vision | macOS/iOS | Native high-quality OCR | N/A |
| Windows OCR | Windows | Native Windows OCR API | N/A |

## Audio Transcription

Convert speech to searchable text.

| Tool | Description | Stars |
|------|-------------|-------|
| [Whisper](https://github.com/openai/whisper) | OpenAI's speech recognition model | ![GitHub stars](https://img.shields.io/github/stars/openai/whisper) |
| [whisper.cpp](https://github.com/ggerganov/whisper.cpp) | High-performance C++ port of Whisper | ![GitHub stars](https://img.shields.io/github/stars/ggerganov/whisper.cpp) |
| [faster-whisper](https://github.com/SYSTRAN/faster-whisper) | 4x faster Whisper with CTranslate2 | ![GitHub stars](https://img.shields.io/github/stars/SYSTRAN/faster-whisper) |
| [WhisperX](https://github.com/m-bain/whisperX) | Whisper with word-level timestamps and speaker diarization | ![GitHub stars](https://img.shields.io/github/stars/m-bain/whisperX) |
| [Parakeet (NVIDIA NeMo)](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v2) | Fast, accurate ASR models that top open ASR leaderboards | N/A (model) |
| [Moonshine](https://github.com/moonshine-ai/moonshine) | Fast on-device speech recognition for edge and real-time use | ![GitHub stars](https://img.shields.io/github/stars/moonshine-ai/moonshine) |
| [speaches](https://github.com/speaches-ai/speaches) | OpenAI-compatible local STT/TTS server (formerly faster-whisper-server) | ![GitHub stars](https://img.shields.io/github/stars/speaches-ai/speaches) |
| [Vosk](https://github.com/alphacep/vosk-api) | Offline speech recognition | ![GitHub stars](https://img.shields.io/github/stars/alphacep/vosk-api) |

## Context for Coding

AI coding assistants that use project, codebase, and screen context.

| Tool | Context Features | Stars |
|------|-----------------|-------|
| [Claude Code](https://github.com/anthropics/claude-code) | Anthropic's agentic coding CLI with full-repo context | ![GitHub stars](https://img.shields.io/github/stars/anthropics/claude-code) |
| [Cline](https://github.com/cline/cline) | Autonomous coding agent in VS Code with codebase context | ![GitHub stars](https://img.shields.io/github/stars/cline/cline) |
| [OpenHands](https://github.com/OpenHands/OpenHands) | Open platform for AI software-engineering agents (formerly OpenDevin) | ![GitHub stars](https://img.shields.io/github/stars/OpenHands/OpenHands) |
| [Continue](https://github.com/continuedev/continue) | Codebase context, custom context providers | ![GitHub stars](https://img.shields.io/github/stars/continuedev/continue) |
| [Aider](https://github.com/Aider-AI/aider) | Git-aware AI pair programming | ![GitHub stars](https://img.shields.io/github/stars/Aider-AI/aider) |
| [Tabby](https://github.com/TabbyML/tabby) | Self-hosted AI coding assistant | ![GitHub stars](https://img.shields.io/github/stars/TabbyML/tabby) |
| [Cursor](https://cursor.com/) | Full codebase indexing | N/A (closed) |

## Research & Papers

Academic work on context-aware AI systems.

- [Generative Agents: Interactive Simulacra of Human Behavior](https://arxiv.org/abs/2304.03442) - Stanford's paper on agents with memory
- [MemGPT: Towards LLMs as Operating Systems](https://arxiv.org/abs/2310.08560) - Memory management for LLMs
- [Voyager: An Open-Ended Embodied Agent](https://arxiv.org/abs/2305.16291) - Lifelong learning agent with memory
- [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366) - Self-reflection for agents

## Building with Context

### Tutorials & Guides

- [Building a Second Brain with AI](https://www.buildingasecondbrain.com/) - Tiago Forte's methodology
- [Context Engineering](https://dev.to/contextspace_/the-10-best-context-engineering-open-source-projects-in-2025-4f94) - Best practices for context

### Integration Examples

- [Screenpipe pipes](https://github.com/screenpipe/screenpipe/tree/main/pipes) - Reference automations that consume screen and audio context
- [Screenpipe docs](https://docs.screenpi.pe) - Build apps and agents on top of screen context
- [Screenpipe TypeScript SDK](https://www.npmjs.com/package/@screenpipe/js) - Query screen recordings, audio, and UI elements from JS/TS

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
