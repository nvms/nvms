# nvms

Hello.

## Projects

### [@eaccess/auth](https://github.com/nvms/eaccess)

Postgres-backed auth for Express. Sessions, remember-me, email verification, password reset, OAuth (GitHub/Google/Azure), role bitmasks, 2FA (TOTP + email/SMS OTP + backup codes), activity logging.

### [@threaded/ai](https://github.com/nvms/threaded)

Composable, provider-agnostic LLM workflow library. Functional pipelines over immutable conversation contexts. Supports OpenAI, Anthropic, Gemini, xAI, Ollama. Tool execution with approval, streaming, structured outputs, threads, embeddings, image generation, MCP integration.

### [trend](https://github.com/nvms/trendr)

Terminal UI renderer with JSX components and SolidJS-style signals. Direct-mode rendering with flexbox layout, double-buffered cell diffing, and minimal ANSI output. Zero dependencies.

### [prsm](https://github.com/prsmjs)

Small, focused utilities. All ESM, zero or minimal dependencies.

| Package | | | Description |
|---------|---|---|-------------|
| [@prsm/realtime](https://github.com/prsmjs/realtime) | ![test](https://github.com/prsmjs/realtime/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/realtime) | Distributed WebSocket framework with Redis-backed rooms, records, presence, channels, collections, and persistence |
| [@prsm/devtools](https://github.com/prsmjs/devtools) | | ![npm](https://img.shields.io/npm/v/@prsm/devtools) | Read-only Express middleware dashboard for observing @prsm infrastructure at runtime |
| [@prsm/cron](https://github.com/prsmjs/cron) | ![test](https://github.com/prsmjs/cron/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cron) | Redis-backed distributed cron scheduler with leader election and cron expression support |
| [@prsm/queue](https://github.com/prsmjs/queue) | ![test](https://github.com/prsmjs/queue/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/queue) | Redis-backed distributed task queue with per-tenant grouped concurrency |
| [@prsm/lock](https://github.com/prsmjs/lock) | ![test](https://github.com/prsmjs/lock/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/lock) | Distributed locking primitives for Redis - mutex and semaphore |
| [@prsm/cells](https://github.com/prsmjs/cells) | ![test](https://github.com/prsmjs/cells/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/cells) | Reactive computation graph with async-first distributed coordination via Redis |
| [@prsm/limit](https://github.com/prsmjs/limit) | ![test](https://github.com/prsmjs/limit/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/limit) | Redis-backed rate limiting - token bucket, sliding window, leaky bucket |
| [@prsm/from](https://github.com/prsmjs/from) | ![test](https://github.com/prsmjs/from/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/from) | Fluent, immutable query builder for arrays of objects |
| [@prsm/fsm](https://github.com/prsmjs/fsm) | ![test](https://github.com/prsmjs/fsm/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/fsm) | Non-deterministic finite state machine with persistence |
| [@prsm/workflow](https://github.com/prsmjs/workflow) | ![test](https://github.com/prsmjs/workflow/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/workflow) | Durable workflow engine with explicit steps, persisted execution state, retries, and inspectable history |
| [@prsm/hash](https://github.com/prsmjs/hash) | ![test](https://github.com/prsmjs/hash/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/hash) | Salted string hashing with self-describing hash format |
| [@prsm/ids](https://github.com/prsmjs/ids) | ![test](https://github.com/prsmjs/ids/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ids) | Reversible integer-to-short-string obfuscation |
| [@prsm/ms](https://github.com/prsmjs/ms) | ![test](https://github.com/prsmjs/ms/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@prsm/ms) | Human-friendly time expression parser |

### [gridwork](https://github.com/gridworkjs)

Composable spatial data structures for JavaScript. Every index implements the same query interface - learn one API, pick the data structure that fits your access pattern.

| Package | | | Description |
|---------|---|---|-------------|
| [@gridworkjs/core](https://github.com/gridworkjs/core) | ![test](https://github.com/gridworkjs/core/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/core) | Geometry primitives (point, rect, circle) and spatial index protocol |
| [@gridworkjs/quadtree](https://github.com/gridworkjs/quadtree) | ![test](https://github.com/gridworkjs/quadtree/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/quadtree) | Quadtree spatial index for sparse, uneven point and region data |
| [@gridworkjs/rtree](https://github.com/gridworkjs/rtree) | ![test](https://github.com/gridworkjs/rtree/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/rtree) | R-tree spatial index with bulk loading for rectangles and polygons |
| [@gridworkjs/hashgrid](https://github.com/gridworkjs/hashgrid) | ![test](https://github.com/gridworkjs/hashgrid/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/hashgrid) | Spatial hash grid for uniform distributions and fast neighbor lookups |
| [@gridworkjs/kd](https://github.com/gridworkjs/kd) | ![test](https://github.com/gridworkjs/kd/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/kd) | KD-tree for static point sets and nearest-neighbor queries |
| [@gridworkjs/query](https://github.com/gridworkjs/query) | ![test](https://github.com/gridworkjs/query/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@gridworkjs/query) | Higher-level queries (radius, knn, ray, within) against any index |

### [jsondelta](https://github.com/jsondelta)

The fastest JSON structural operations in any JavaScript runtime. Zig-powered diffing, patching, and merging with WebAssembly and pure JS fallback.

| Package | | | Description |
|---------|---|---|-------------|
| [@jsondelta/diff](https://github.com/jsondelta/diff) | ![test](https://github.com/jsondelta/diff/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@jsondelta/diff) | Structural JSON diffing with Zig-compiled WebAssembly engine |
| [@jsondelta/patch](https://github.com/jsondelta/patch) | ![test](https://github.com/jsondelta/patch/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@jsondelta/patch) | Patch application and delta inversion |
| [@jsondelta/merge](https://github.com/jsondelta/merge) | ![test](https://github.com/jsondelta/merge/actions/workflows/test.yml/badge.svg) | ![npm](https://img.shields.io/npm/v/@jsondelta/merge) | Three-way merge with conflict detection |

### [procmod](https://github.com/procmod)

Composable runtime game instrumentation primitives for Rust. Process memory, pattern scanning, function hooking, struct mapping, and overlay rendering.

| Crate | | | Description |
|-------|---|---|-------------|
| [procmod-core](https://github.com/procmod/procmod-core) | ![test](https://github.com/procmod/procmod-core/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-core) | Cross-platform process memory read/write |
| [procmod-scan](https://github.com/procmod/procmod-scan) | ![test](https://github.com/procmod/procmod-scan/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-scan) | Fast pattern and signature scanning for byte slices |
| [procmod-layout](https://github.com/procmod/procmod-layout) | ![test](https://github.com/procmod/procmod-layout/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-layout) | Struct mapping with pointer chain traversal via derive macros |
| [procmod-hook](https://github.com/procmod/hook) | ![test](https://github.com/procmod/hook/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-hook) | Inline function hooking and detouring |
| [procmod-overlay](https://github.com/procmod/overlay) | ![test](https://github.com/procmod/overlay/actions/workflows/test.yml/badge.svg) | ![crates.io](https://img.shields.io/crates/v/procmod-overlay) | Game overlay rendering with transparent click-through windows |
