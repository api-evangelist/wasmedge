# WasmEdge

WasmEdge is a lightweight, high-performance, and extensible WebAssembly runtime for cloud native, edge, and decentralized applications. It powers serverless apps, embedded functions, microservices, smart contracts, and IoT devices. WasmEdge is a CNCF sandbox project providing an LLVM-based AoT compiler for maximum performance, supporting WASI extensions for non-blocking networking, database access, and AI inference via TensorFlow, PyTorch, and OpenVINO.

**Website:** https://wasmedge.org  
**Documentation:** https://wasmedge.org/docs/  
**GitHub:** https://github.com/WasmEdge/WasmEdge  
**APIs.json:** https://raw.githubusercontent.com/api-evangelist/wasmedge/refs/heads/main/apis.yml

## Tags

Cloud Native, CNCF, Edge Computing, High Performance, Runtime, Serverless, Wasm, WebAssembly

---

## APIs & SDKs

### WasmEdge C API

Low-level interface for embedding the WasmEdge runtime into C/C++ host applications. Full access to module instantiation, function invocation, memory access, and plugin management.

- **Documentation:** https://wasmedge.org/docs/embed/c/intro/
- **GitHub:** https://github.com/WasmEdge/WasmEdge

### WasmEdge Rust SDK

Idiomatic Rust bindings for the WasmEdge C API. Supports module loading, instantiation, host function definitions, and plugin integration from Rust.

- **Documentation:** https://wasmedge.org/docs/embed/rust/intro/
- **GitHub:** https://github.com/WasmEdge/wasmedge-rust-sdk

### WasmEdge Go SDK

Go language bindings for embedding WasmEdge in Go applications. Load and execute WebAssembly modules from Go with host function support.

- **Documentation:** https://wasmedge.org/docs/embed/go/intro/

### WasmEdge Node.js SDK

JavaScript bindings for calling WebAssembly functions from Node.js applications.

- **Documentation:** https://wasmedge.org/docs/embed/node/

### WasmEdge Plugin System

Extend the runtime with custom host function packages developed in Rust or C/C++. Plugins include wasi_nn (TensorFlow/PyTorch/OpenVINO AI), wasi_crypto, wasi_logging, and WASM-BPF.

- **Documentation:** https://wasmedge.org/docs/contribute/plugin/

---

## Artifacts

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/wasmedge-config-schema.json](json-schema/wasmedge-config-schema.json) | WasmEdge runtime configuration schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/wasmedge-config-structure.json](json-structure/wasmedge-config-structure.json) | WasmEdge configuration field structure |

### JSON-LD Contexts

| File | Description |
|------|-------------|
| [json-ld/wasmedge-context.jsonld](json-ld/wasmedge-context.jsonld) | JSON-LD context for WasmEdge vocabulary |

### Examples

| File | Description |
|------|-------------|
| [examples/wasmedge-rust-sdk-example.json](examples/wasmedge-rust-sdk-example.json) | Load and run a Wasm function via Rust SDK |
| [examples/wasmedge-cli-example.json](examples/wasmedge-cli-example.json) | CLI commands for running Wasm modules |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/wasmedge-vocabulary.yml](vocabulary/wasmedge-vocabulary.yml) | Domain vocabulary: Runtime, AoT, WASI, WASI-NN, Plugin, Host Function, Gas Meter |

---

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
