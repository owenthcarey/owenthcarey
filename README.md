<h1 align="center">Hi, I'm Owen Carey</h1>

<p align="center">
  <em>I build open-source frameworks that bring Python to native mobile and web UI and make code portable across language boundaries.</em>
</p>

<p align="center">
  <a href="https://github.com/owenthcarey?tab=repositories">Repositories</a> ·
  <a href="https://github.com/owenthcarey?tab=stars">Stars</a> ·
  <a href="https://github.com/owenthcarey?tab=followers">Followers</a>
</p>

---

## About

My work centers on two related problems: writing UI in Python for platforms that don't expect it and moving code safely across language boundaries. PythonNative compiles declarative Python components to real UIKit and AndroidX views, Wybthon brings a signals-first reactive model to the browser through Pyodide, and WeaveFFI generates type-safe bindings for eleven languages from a single IDL. These are the projects I'm actively maintaining.

## Featured Projects

### [PythonNative](https://github.com/pythonnative/pythonnative)

**Build native Android and iOS apps in Python.**

PythonNative is a cross-platform framework with a declarative, React-like component model: function components, hooks (`use_state`, `use_effect`, `use_navigation`), automatic reconciliation, and a pure-Python, Yoga-style flexbox engine. It compiles to real `UIKit` and `AndroidX` views via `rubicon-objc` and `Chaquopy`, with no JavaScript bridge in between. The CLI scaffolds projects, and `pn run --hot-reload` ships Fast Refresh out of the box.

`Python` · `iOS / UIKit` · `Android / AndroidX` · `Chaquopy` · `rubicon-objc`

[![Stars](https://img.shields.io/github/stars/pythonnative/pythonnative?style=flat&logo=github&color=181717)](https://github.com/pythonnative/pythonnative/stargazers) [![Forks](https://img.shields.io/github/forks/pythonnative/pythonnative?style=flat&logo=github&color=181717)](https://github.com/pythonnative/pythonnative/network/members) [![Language](https://img.shields.io/github/languages/top/pythonnative/pythonnative?style=flat)](https://github.com/pythonnative/pythonnative) [![Last commit](https://img.shields.io/github/last-commit/pythonnative/pythonnative?style=flat)](https://github.com/pythonnative/pythonnative/commits)

---

### [Wybthon](https://github.com/wybthon/wybthon)

**Build interactive web apps in Python, no JavaScript required.**

Wybthon is a client-side SPA framework powered by Pyodide. It uses a signals-first reactive model inspired by SolidJS: function components run once at mount, and embedded signal getters become reactive holes that update only the affected DOM node. The framework ships with a virtual DOM, client-side router, context API, forms with validation, flow-control primitives, error boundaries, Suspense, and a dev server with SSE-based hot reload.

`Python` · `Pyodide` · `Signals` · `WebAssembly` · `SPA`

[![Stars](https://img.shields.io/github/stars/wybthon/wybthon?style=flat&logo=github&color=181717)](https://github.com/wybthon/wybthon/stargazers) [![Forks](https://img.shields.io/github/forks/wybthon/wybthon?style=flat&logo=github&color=181717)](https://github.com/wybthon/wybthon/network/members) [![Language](https://img.shields.io/github/languages/top/wybthon/wybthon?style=flat)](https://github.com/wybthon/wybthon) [![Last commit](https://img.shields.io/github/last-commit/wybthon/wybthon?style=flat)](https://github.com/wybthon/wybthon/commits)

---

### [WeaveFFI](https://github.com/weavefoundry/weaveffi)

**Type-safe bindings for eleven languages from a single IDL.**

WeaveFFI generates idiomatic packages for C, C++, Swift, Kotlin/Android, Node.js, WebAssembly, Python, .NET, Dart, Go, and Ruby from one YAML, JSON, or TOML definition. Every target speaks to the same stable C ABI, so adding a new platform is a code-gen change rather than a rewrite. The CLI handles validation, linting, diffing, formatting, IDL extraction from annotated Rust, and schema migration via `weaveffi upgrade`.

`Rust` · `C ABI` · `IDL` · `Code generation` · `cargo`

[![Stars](https://img.shields.io/github/stars/weavefoundry/weaveffi?style=flat&logo=github&color=181717)](https://github.com/weavefoundry/weaveffi/stargazers) [![Forks](https://img.shields.io/github/forks/weavefoundry/weaveffi?style=flat&logo=github&color=181717)](https://github.com/weavefoundry/weaveffi/network/members) [![Language](https://img.shields.io/github/languages/top/weavefoundry/weaveffi?style=flat)](https://github.com/weavefoundry/weaveffi) [![Last commit](https://img.shields.io/github/last-commit/weavefoundry/weaveffi?style=flat)](https://github.com/weavefoundry/weaveffi/commits)
