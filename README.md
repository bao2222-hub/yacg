# YACG

> **Yet Another Chess GUI**

YACG is a cross-platform, open-source chess GUI that combines the strength of modern chess engines with the personality of Large Language Models (LLMs).

Instead of replacing traditional chess engines, YACG lets each component do what it does best:

*  **Chess engines** (Stockfish, Lc0, ShashChess, etc.) are responsible for playing chess and evaluating positions.
*  **LLMs** (Ollama, llama.cpp, OpenAI-compatible APIs, etc.) are responsible for commentary, coaching, role-playing, and interaction.
*  **YACG** acts as the bridge between them, providing a simple, modular, and customizable desktop experience.

It will look like:
           YACG
             │
      ┌──────┴──────┐
      │             │
 Chess Engine      LLM
 (Stockfish...) (Ollama...)
 
## Project Goals

* Cross-platform desktop application (Windows, Linux, macOS)
* Modular engine management
* Support multiple UCI chess engines
* Support multiple LLM backends
* Customizable character personalities
* Open-source and easy to extend

## Roadmap

| Feature                       | Status         |
| ----------------------------- | -------------- |
| Project initialization        | Completed      |
| README                        | In Progress    |
| Tauri application             | Planned        |
| Chess board GUI               | Planned        |
| UCI engine integration        | Planned        |
| Stockfish support             | Planned        |
| Lc0 support                   | Planned        |
| LLM backend interface         | Planned        |
| Ollama support                | Planned        |
| OpenAI-compatible API support | Planned        |
| Character system              | Planned        |
| Character packs               | Planned        |
| Engine downloader             | Planned        |
| Settings page                 | Planned        |
| GitHub Actions (CI/CD)        | Planned        |
| First public release          | Planned        |


## Philosophy

YACG does not attempt to replace chess engines with LLMs.

Instead, it combines the strengths of both:

* Chess engines calculate.
* LLMs communicate.
* YACG orchestrates.

## License

This project is licensed under the MIT License.
