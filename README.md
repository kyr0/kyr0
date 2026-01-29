### Hi 👋, I'm Aron

> I’m a systems thinker and software engineer with a deep focus on solving hard, often overlooked problems - especially in areas like web development, algorithm design, low-level optimization, language engineering, and applied AI. My work is driven by a simple principle: **build things that are genuinely useful and intellectually honest.**

> Over the years, I’ve created and contributed to a wide range of client projects, OSS libraries, tools, and demos that push technical boundaries - from web frameworks, ultra-fast math libraries, and compact NLP systems for hybrid search and language identification, to encoders/decoders, domain-specific languages (DSLs), browser extensions, PWAs, agentic graph-reasoning workflows, and advanced multicore WebAssembly or JIT-optimized solutions for the web platform.

> I value *clarity*, *correctness*, and *elegance* over trends or hype - and prefer deep, focused work over shallow visibility.

> If you’re here because something I built helped you - or something I posted inspired you - that’s the best outcome I could hope for.
 
- 🛠️ These days, I'm building AI-driven web apps, libraries and open source software engineering tools
    - [defuss](https://github.com/kyr0/defuss) - Frustrated about the complexity in modern web dev, I've created my own vision of how simple, deterministic, small, elegant and extremely performant a synergistic React-, Next.js-, jQuery clone could be -- this is pretty complete and stable now after 6 years in development 
    - [easy-erechnung](https://github.com/kyr0/easy-erechnung) - The only cross-platform, fully open-source and AI-supported app to create valid Factur-X/ZuGPFeRD invoices (EU) - currently in beta, 1 year in development
    - [update-agents-md](https://github.com/kyr0/update-agents-md) - Now that frontier LLMs support context sizes beyond 1M tokens and approach near-perfect recall, we can boost (local maxima) AI-assisted coding/codegen by packing all code into one prompt and let multiple models battle for the best solution, even without IDEs and Claude Code/OpenCode/Codex/Antigravity/Cursor etc. - sounds counter-intuitive, but it's extremely  useful
    - A **stealth** project that is too dangerous to reveal. [Hint](https://www.linkedin.com/posts/aronhomberg_how-to-crack-a-diamond-or-how-i-unexpectedly-activity-7292827345915101184-4ReG?utm_source=share&utm_medium=member_desktop&rcm=ACoAAALSPsgBQk4N2Bzi2ys34NEmLX22pUgFweY)
- 🛠️ For bread & butter:
    - [NeuraMancer.de](https://neuramancer.de) - Reliable deepfake detection (local AI, inference, training, ML research, data pipelines, APIs, web apps) - since end of 2024
    - [KI.M](https://medien-bayern.de/ki-kompetenzzentrum-medien) - Prototyping advanced AI applications for media houses; building one of the first AI labs in bavaria (local AI, inference, training, ML research) - since early 2025
    - [HYOBAN.ai](https://hyoban.ai) - Professional, AI-driven review management, analytics & competitor monitoring (cloud AI, APIs, ML research, agent engineering, prompt engineering, OpenAI startup partner) - since early 2024
- 🔬 Current focus interest: 
    1. (Local) Agentic systems/autonomous bots, neuro-symbolic AI research, vector retrieval/indexing, NLP algorithms in general, small-scale model architecture and training, novel ML algos from scratch - beyond backprop and classic algos - frontier AI architecture research - fusion of SoTA non-AI algos with SoTA AI models
    2. High performance web tech (WebAssembly, SIMD, WebGPU, JIT optimization & co.), Rust-based multicore WebAssembly ports (prev. Emscripten/C)
    3. LLMs, GPTs, RLHF, GRPO, QLoRA, ... (every non-vapor-paper)
    4. ASTs, stack-based executors, DSLs
    5. NLP/search algos, tokenizers, encoders
    6. High performance audio synthesis, routing, sampling, mixing, and analysis algorithms
    7. Web frameworks (see my work on [`defuss`](https://github.com/kyr0/defuss), which re-invents the whole frontend web-tech wheel)
- Some infra-tools for you (systems engineer focus):
  - Qwen3-Omni MLLM 30B series vLLM Docker Container deployment scripts [qwen3-omni-vllm-docker](https://github.com/kyr0/qwen3-omni-vllm-docker) 

### EXPERIMENTAL

- 🔬 Novel algorithms and computer science / research projects I'm working on:
  - I'm in the process of moving the most useful algorithms under the `defuss` framework umbrella for production use. e.g. see [`defuss/fastmath`](https://github.com/kyr0/defuss/blob/main/packages/fastmath/src/vector.rs)'s vector lib - it provides 25 GFLOP/s vector calculations in-browser (!!!), while `fast-dotproduct` was already faster than JS with about 2 GLOP/s..
  - [Ringbuf.js](https://github.com/padenot/ringbuf.js) - TypeScript port and JIT optimizations -- wait-free thread-safe single-consumer single-producer ring buffer using SharedArrayBuffer. [PR](https://github.com/padenot/ringbuf.js/pull/29)
  - [RedakTool.ai](https://github.com/kyr0/redaktool) - Browser extension for editors and professionals engaged in text-related research, writing, and evaluation tasks. 
  - [langdetect-ts](https://github.com/kyr0/langdetect-ts) - Port of Google LangDetect, the state-of-the-art language ngram-based language detection (identification) library to TypeScript. Used in `liquiprompt` and RedakTool. [EXPERIMENTAL. In transit to `defuss/langid`](https://github.com/kyr0/defuss/tree/main/packages/langid)
  - [fast-dotproduct](https://github.com/kyr0/fast-dotproduct) - Aims to be the fastest dot product calculation library for in-browser use. Backbone of RedakTool's vectorstore. [EXPERIMENTAL. In transit to `defuss/fastmath`](https://github.com/kyr0/defuss/tree/main/packages/fastmath)
  - [vectorstore](https://github.com/kyr0/vectorstore/) - In-browser, vector store featuring very fast vector indexing, storage, serialization, product quantization and search (exact, kMeans, HNSW) balancing search quality and memory/computational constraints. Backbone of RedakTool's archive and NewsRadar topic following algorithm. Also used in `liquiprompt` for few-shot optimized exemplars. [EXPERIMENTAL. In transit to `defuss/vectorlite`](https://github.com/kyr0/defuss/tree/main/packages/vectorlite)
  - [quality-prompts-js](https://github.com/kyr0/quality-prompts-js) - Write Quality Prompts using auto-optimization. Use and evaluate prompting techniques quickly. Learnings used in `liquiprompt` for automatic prompt optimizations. [EXPERIMENTAL. In transit to `defuss/apl` examples](https://github.com/kyr0/defuss/tree/main/packages/apl)
  - [liquiprompt](https://github.com/kyr0/liquiprompt) - The prompt language used in RedakTool. Simple but powerful prompt and RAG workflow templating language (DSL) featuring D(A/C)G parse/test/run orchestration. [EXPERIMENTAL. In transit to `defuss/apl`](https://github.com/kyr0/defuss/tree/main/packages/apl)
  - [clientside-search](https://github.com/kyr0/clientside-search) - "Lucene in the browser + Node.js"; highly efficient, isomorphic, full-featured, multilingual text search engine library, providing full-text search, fuzzy matching, document indexing and more [EXPERIMENTAL. In transit to `defuss/search`]([https://github.com/kyr0/defuss/tree/main/packages/apl](https://github.com/kyr0/defuss/tree/main/packages/search))
  - [easy-embeddings](https://github.com/kyr0/easy-embeddings) - In-browser vector embeddings made easy using WebGPU and WebAssembly acceleration. 
  - [cross-llm](https://github.com/kyr0/cross-llm) - Abstract LLM/vector embedding implementation. A universal library to integrate with LLMs and Vector Embedding endpoints. Supports Node.js, Deno, Bun, Service Workers, Web Extensions. [ABANDONED. Use `@vercel/ai` - `defuss/apl` has a standard OpenAI adapter per-runtime]
  - [offline-geocode-city](https://github.com/kyr0/offline-geocode-city) - smallest and fastest offline reverse geocoder for country/city on NPM, in-browser, Node.js, service worker, using S2 cell geometry
  - [@jsheaven/perf](https://github.com/jsheaven/perf) - an algorithm to estimate the average runtime and time-complexity (big O notation) of (a)sync algorithms in JavaScript/TypeScript projects
  - [brotli-unicode](https://github.com/kyr0/brotli-unicode) - a novel algorithm for encoding/decoding and character level compression/decompression with character-level compression rates of >500%. The compressed data is copy-pasteable without data loss
  - [base-unicode](https://github.com/kyr0/base-unicode) - a novel algorithm for encoding/decoding in a Unicode symbol plane that makes use of printable characters of all kinds of languages; this allows for thousands of symbols to be used instead of only 64 like in base64
- 🌟 Recently completed apps/websites:
  - [bootsector.games](https://bootsector.games) - learning and experimenting with NASM x86 assembly and bootsector game development in-browser; implemented the `INT3` step-debugging instruction in the Rust-based v86   - 
  - [milkymilky.rocks](https://milkymilky.rocks) - WinAmp style, shader based music visualization, rendered on the GPU wie WebGL/WebGPU in Electron
- 📚 My top completed JavaScript/TypeScript libraries/frameworks/developer tools:
  - [@jsheaven/easybuild](https://github.com/jsheaven/easybuild) - `esbuild` based, super-fast and easy IIFE, ESM and CJS bundler for JS and TS; primarily for libraries, API- and CLI projects [ABANDONED. Use `pkgroll` or `esbuild` directly.]
  - [@jsheaven/create-from-git](https://github.com/jsheaven/create-from-git) - scaffolds a new project using `git checkout` and smart, in-file string replacements. Comes with an API and CLI: `npx create-from-git`. Runs on Mac, Windows and Linux. [TRANSITIONED: `create-defuss`](https://github.com/kyr0/defuss/tree/main/packages/create-defuss)
  - [@jsheaven/simply-persist](https://github.com/jsheaven/simply-persist) - simple, solid CRUD-only client-side storage with session/localStorage persistency [TRANSITIONED: `defuss/webstroage` core library](https://github.com/kyr0/defuss/tree/main/packages/defuss/src/webstorage)
  - [@jsheaven/observed](https://github.com/jsheaven/observed) - explicit, `Proxy`-based reactive pattern implementation for objects of any depth [TRANSITIONED: `defuss/store` core library](https://github.com/kyr0/defuss/blob/main/packages/defuss/src/store/store.ts)
  - [@jsheaven/validalli](https://github.com/jsheaven/validalli) - functional, well-tested, framework-agnostic (form) validation library based on the composition pattern  [TRANSITIONED: `defuss/transval` core library]([https://github.com/kyr0/defuss/tree/main/packages/defuss/src/webstorage](https://github.com/kyr0/defuss/tree/main/packages/transval))
- ⚒️ Re-implemented for educational purposes ("True knowledge lies in creation")
  - [vanil](https://github.com/kyr0/vanil) - static website builder similar to [Astro.build](https://astro.build), Next.js and Gatsby (archived; Astro.build improved alot and suits my needs these days) [ABANDONED. Use `defuss/ssg` - simple static site genration]
  - [PCemOnMac/PCemV17macOS](https://github.com/PCemOnMac/PCemV17macOS) - ported PCem, an emulator for old computers, to run dated software on DOS, Windows 3.11, Windows 95, Windows 98 to Mac  
  - [@sprintype-org/springtype](https://github.com/springtype-org/springtype) - a 4k nano-framework with a Virtual DOM implementation and React-like features; [Colivery](https://github.com/colivery) is built with it [ABANDONED. Led to the development of `defuss`]
  - [nes-ui-react](https://github.com/kyr0/nes-ui-react) - a SASS/SCSS design framework for an 8-bit UI reminisence look and feel, re-implemented the patterns of prominent UI frameworks; [bootsector.games](https://bootsector.games) is built with it [NOTICE: Might transit to `defuss/retro-ui` one day...]
  - [Extanium2](https://github.com/kyr0/Extanium2) - open-source re-implementation of ExtJS 4 
