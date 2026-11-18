# StarBuddy

[简体中文](README.md) | [English](README.en.md)

<img src="assets/brand/starbuddy.svg" alt="StarBuddy" width="96" height="96">

StarBuddy is a desktop companion built around Xingya, the little star from [Starclip](https://github.com/StarDreamTech/Starclip). The goal is to give it a request and an AI key: it would choose the project, local agent, model, reasoning level, session and skills, follow the job, and retain what it learned.

**What works now:** this is a phase-zero preview. The frontend shell, character growth system and gateway protocol draft are here. The background service and adapters for agents such as Claude Code and Codex are not implemented.

## Develop and preview
```sh
npm install
npm test
npm run build
npm run dev
```
Open `http://127.0.0.1:1420/`. The preview uses in-memory demo data for expressions, movement and interactions. Transparent windows, dragging and edge snapping require the future Tauri integration. The PR verification job produces a `starbuddy-preview` artifact with a screenshot and the built `dist/` directory.

![Browser preview of Xingya](docs/starbuddy-browser-preview.png)

## Project notes
- [Architecture and gateway protocol](docs/architecture.md)
- [Character](docs/starpet.md), [design](docs/starpet-design.md) and [growth](docs/starpet-growth.md)
- [Artwork provenance](docs/artwork-rights.md)

[MIT license](LICENSE). Xingya is an original character; its design history is recorded in the project notes.
