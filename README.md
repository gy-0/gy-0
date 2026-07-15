# Yuan · gy-0

**Software engineer** · McMaster University M.Eng. (CAS) · Building desktop & AI tooling

Hamilton, ON · [github.com/gy-0](https://github.com/gy-0)

---

### About

I work across **desktop apps, TypeScript/React, and AI-assisted product surfaces**.  
I care about shipping things people actually use — debugging hard edge cases, tightening auth/UX, and keeping local pipelines honest.

Currently exploring **OCR → LLM → image generation** systems, media transcription, and contributions to open-source tools I rely on every day.

---

### Open source

#### [CipherTalk / 密语](https://github.com/ILoveBingLu/CipherTalk)
WeChat chat archive viewer · Electron · TypeScript · **1.1k+ ★**

Merged contributions (2026):

| PR | Impact |
| --- | --- |
| [#250](https://github.com/ILoveBingLu/CipherTalk/pull/250) · OpenRouter connection test | Fixed false “connection success” when API keys were invalid — `/models` is unauthenticated on OpenRouter, so tests looked green until chat failed with 401 |
| [#253](https://github.com/ILoveBingLu/CipherTalk/pull/253) · STT transcript cache | Fixed cache path split that re-ran cloud speech recognition on “re-clone”, burning ASR quota for already-transcribed voice messages |

Also authored the upstream issue: [#249](https://github.com/ILoveBingLu/CipherTalk/issues/249)

> Contributor on a project I use daily — still actively following `main` and planning more fixes.

---

### Selected projects

| Project | What it is |
| --- | --- |
| **[Imagio](https://github.com/gy-0/Imagio)** | macOS desktop app (Tauri 2 + React + Rust): image → OCR → LLM prompt refine → text-to-image. Built for my M.Eng. report *Optical Character Recognition to Image Generation*. |
| **[ScribeStudio](https://github.com/gy-0/ScribeStudio)** | Desktop media transcription workbench — local audio/video, ASR, timeline segments, export to SRT / VTT / Markdown. |
| **[ElmoChatProxy](https://github.com/gy-0/ElmoChatProxy)** | OpenAI-compatible proxy for Elmo Chat — streaming, multi-turn, Vercel-ready. |

---

### Stack

```text
Languages   TypeScript · JavaScript · Python · Rust · Java · Swift
Frontend    React · Vite · Next.js · Tauri WebView
Desktop     Electron · Tauri 2
Backend     Node.js · OpenAI-compatible APIs · serverless
Data / AI   OCR (Tesseract) · ASR · LLM tooling · local + cloud pipelines
Tooling     Git · GitHub · npm · macOS native packaging
```

---

### Focus areas

- **Desktop product engineering** — packaging, native bridges, real-user workflows  
- **AI integration that fails loudly** — correct auth checks, cache correctness, cost control  
- **Inspectable pipelines** — OCR / ASR / generation steps users can see and fix  

---

### Currently

- Shipping and refining personal desktop tools (Imagio, ScribeStudio)  
- Long-term contributor mindset on [CipherTalk](https://github.com/ILoveBingLu/CipherTalk)  
- Always open to sharp bug reports and small, high-signal PRs  

---

<p align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=gy-0&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true" height="140" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gy-0&layout=compact&theme=transparent&hide_border=true&langs_count=8" height="140" alt="Top languages" />
</p>

---

*Think different. Ship carefully.*
