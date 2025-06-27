### Hi 👋, I'm Aron

> I’m a systems thinker and software engineer with a deep focus on solving hard, often overlooked problems - especially in areas like web development, algorithm design, low-level optimization, language engineering, and applied AI. My work is driven by a simple principle: **build things that are genuinely useful and intellectually honest.**

> Over the years, I’ve created and contributed to a wide range of client projects, OSS libraries, tools, and demos that push technical boundaries - from web frameworks, ultra-fast math libraries, and compact NLP systems for hybrid search and language identification, to encoders/decoders, domain-specific languages (DSLs), browser extensions, PWAs, agentic graph-reasoning workflows, and advanced multicore WebAssembly or JIT-optimized solutions for the web platform.

> I value *clarity*, *correctness*, and *elegance* over trends or hype - and prefer deep, focused work over shallow visibility.

> If you’re here because something I built helped you - or something I posted inspired you - that’s the best outcome I could hope for.
 
- 🛠️ These days, I'm building AI-driven web apps, libraries and open source software engineering tools
    - [RedakTool.ai](https://github.com/kyr0/redaktool) - Browser extension for editors and professionals engaged in text-related research, writing, and evaluation tasks. 
    - [Ringbuf.js](https://github.com/padenot/ringbuf.js) - TypeScript port and JIT optimizations -- wait-free thread-safe single-consumer single-producer ring buffer using SharedArrayBuffer. [PR](https://github.com/padenot/ringbuf.js/pull/29)
- 🛠️ For bread & butter:
    - [NeuraForge.de](https://neuraforge.de) - Reliable deepfake detection.
    - [KI.M](https://medien-bayern.de/ki-kompetenzzentrum-medien) - Prototyping advanced AI applications for media houses.
    - [HYOBAN.ai](https://hyoban.ai) - Professional, AI-driven review management, analytics & competitor monitoring.
- 🔬 Current focus interest: 
    1. Agentic systems, vector databases, NLP algorithms
    2. High performance web tech (WebAssembly, SIMD, WebGPU, JIT optimization & co.), Rust-based multicore WebAssembly ports (prev. Emscripten/C)
    3. LLMs, GPTs, RLHF, GRPO, QLoRA, ... (every non-vapor-paper)
    4. ASTs, stack-based executors, DSLs
    5. NLP/search algos, tokenizers, encoders
    6. High performance audio synthesis, routing, sampling, mixing, and analysis algorithms
    7. Web frameworks (see my work on [`defuss`](https://github.com/kyr0/defuss), which re-invents the whole frontend web-tech wheel)
- 🔬 Novel algorithms and computer science / research projects I'm working on:
  - [langdetect-ts](https://github.com/kyr0/langdetect-ts) - Port of Google LangDetect, the state-of-the-art language ngram-based language detection (identification) library to TypeScript. Used in `liquiprompt` and RedakTool.
  - [fast-dotproduct](https://github.com/kyr0/fast-dotproduct) - Aims to be the fastest dot product calculation library for in-browser use. Backbone of RedakTool's vectorstore.
  - [vectorstore](https://github.com/kyr0/vectorstore/) - In-browser, vector store featuring very fast vector indexing, storage, serialization, product quantization and search (exact, kMeans, HNSW) balancing search quality and memory/computational constraints. Backbone of RedakTool's archive and NewsRadar topic following algorithm. Also used in `liquiprompt` for few-shot optimized exemplars.
  - [quality-prompts-js](https://github.com/kyr0/quality-prompts-js) - Write Quality Prompts using auto-optimization. Use and evaluate prompting techniques quickly. Learnings used in `liquiprompt` for automatic prompt optimizations.
  - [liquiprompt](https://github.com/kyr0/liquiprompt) - The prompt language used in RedakTool. Simple but powerful prompt and RAG workflow templating language (DSL) featuring D(A/C)G parse/test/run orchestration.
  - [clientside-search](https://github.com/kyr0/clientside-search) - "Lucene in the browser + Node.js"; highly efficient, isomorphic, full-featured, multilingual text search engine library, providing full-text search, fuzzy matching, document indexing and more
  - [easy-embeddings](https://github.com/kyr0/easy-embeddings) - In-browser vector embeddings made easy using WebGPU and WebAssembly acceleration. 
  - [cross-llm](https://github.com/kyr0/cross-llm) - Abstract LLM/vector embedding implementation. A universal library to integrate with LLMs and Vector Embedding endpoints. Supports Node.js, Deno, Bun, Service Workers, Web Extensions. [Status September 2024: In rewrite to wrap @vercel/ai]
  - [offline-geocode-city](https://github.com/kyr0/offline-geocode-city) - smallest and fastest offline reverse geocoder for country/city on NPM, in-browser, Node.js, service worker, using S2 cell geometry
  - [@jsheaven/perf](https://github.com/jsheaven/perf) - an algorithm to estimate the average runtime and time-complexity (big O notation) of (a)sync algorithms in JavaScript/TypeScript projects
  - [brotli-unicode](https://github.com/kyr0/brotli-unicode) - a novel algorithm for encoding/decoding and character level compression/decompression with character-level compression rates of >500%. The compressed data is copy-pasteable without data loss
  - [base-unicode](https://github.com/kyr0/base-unicode) - a novel algorithm for encoding/decoding in a Unicode symbol plane that makes use of printable characters of all kinds of languages; this allows for thousands of symbols to be used instead of only 64 like in base64
- 🌟 Recently completed apps/websites:
  - [bootsector.games](https://bootsector.games) - learning and experimenting with NASM x86 assembly and bootsector game development in-browser; implemented the `INT3` step-debugging instruction in the Rust-based v86   - 
  - [milkymilky.rocks](https://milkymilky.rocks) - WinAmp style, shader based music visualization, rendered on the GPU wie WebGL/WebGPU in Electron
- 📚 My top completed JavaScript/TypeScript libraries/frameworks/developer tools:
  - [@jsheaven/easybuild](https://github.com/jsheaven/easybuild) - `esbuild` based, super-fast and easy IIFE, ESM and CJS bundler for JS and TS; primarily for libraries, API- and CLI projects
  - [@jsheaven/create-from-git](https://github.com/jsheaven/create-from-git) - scaffolds a new project using `git checkout` and smart, in-file string replacements. Comes with an API and CLI: `npx create-from-git`. Runs on Mac, Windows and Linux.
  - [@jsheaven/simply-persist](https://github.com/jsheaven/simply-persist) - simple, solid CRUD-only client-side storage with session/localStorage persistency
  - [@jsheaven/observed](https://github.com/jsheaven/observed) - explicit, `Proxy`-based reactive pattern implementation for objects of any depth
  - [@jsheaven/validalli](https://github.com/jsheaven/validalli) - functional, well-tested, framework-agnostic (form) validation library based on the composition pattern
- ⚒️ Re-implemented for educational purposes ("True knowledge lies in creation")
  - [defuss](https://github.com/kyr0/defuss) - a better React // in fusion and harmony with a lightwight jQuery-like API; full SSR, web-component support; integrated with Astro.build and Vite
  - [vanil](https://github.com/kyr0/vanil) - static website builder similar to [Astro.build](https://astro.build), Next.js and Gatsby (archived; Astro.build improved alot and suits my needs these days)
  - [PCemOnMac/PCemV17macOS](https://github.com/PCemOnMac/PCemV17macOS) - ported PCem, an emulator for old computers, to run dated software on DOS, Windows 3.11, Windows 95, Windows 98 to Mac  
  - [@sprintype-org/springtype](https://github.com/springtype-org/springtype) - a 4k nano-framework with a Virtual DOM implementation and React-like features; [Colivery](https://github.com/colivery) is built with it
  - [nes-ui-react](https://github.com/kyr0/nes-ui-react) - a SASS/SCSS design framework for an 8-bit UI reminisence look and feel, re-implemented the patterns of prominent UI frameworks; [bootsector.games](https://bootsector.games) is built with it
  - [Extanium2](https://github.com/kyr0/Extanium2) - open-source re-implementation of ExtJS 4 
