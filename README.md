# WasmEdge

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
