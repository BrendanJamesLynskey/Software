<!-- portfolio-strip:start (brief 40) -->
<sub>**Brendan Lynskey** · [Portfolio home](https://brendanjameslynskey.github.io/) · [Interactive sites](https://brendanjameslynskey.github.io/#sites)</sub>
<!-- portfolio-strip:end -->




# Software

Software engineering, web development, and computer science repositories — presentations, playgrounds, and reference projects.

---

## Series in this index

| Series | What it covers |
| --- | --- |
| **[Identity &amp; Authorisation](https://brendanjameslynskey.github.io/SW_Hub_Identity_Authorisation/)** | A primer, seven decks on authentication and federation (OAuth, OIDC, SAML, SCIM) and three on authorisation, in reading order |
| **[CI/CD &amp; DevOps](https://brendanjameslynskey.github.io/SW_Hub_CI_CD_DevOps/)** | GitHub, CI/CD, GitHub Actions and Jenkins, ten Docker decks, deploying web apps and microservices, and the Cloud `*aaS` series |
| **[Web Development](https://brendanjameslynskey.github.io/SW_Hub_Web_Development/)** | Twenty-five decks from CSS, TypeScript and browser APIs through React, Node.js and Express to templating, auth, databases, FastAPI and testing |
| **[Algorithms &amp; Data Structures](https://brendanjameslynskey.github.io/SW_Hub_Algorithms_Data_Structures/)** | Complexity, twelve data-structure decks, eleven algorithm decks and the Coding Challenge Coach |
| **[Compilers](https://brendanjameslynskey.github.io/Compilers/)** | Ten decks from the history of compilers and the pipeline to a mini-compiler built end to end |
| **[Cloud `*aaS`](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub)** | Six decks on IaaS, PaaS, FaaS, CaaS, SaaS architecture, cloud security and LLM-as-a-Service |
| **[Simulation Engineering Toolkit](https://brendanjameslynskey.github.io/SimEng_Hub_Toolkit/)** | Fourteen decks on the engineering around a performance simulator (also in the Hardware index) |
| **[Writing VS Code Extensions](https://brendanjameslynskey.github.io/Writing_VSCode_Extensions/)** | A five-part tutorial, from scaffolding to publishing on the Marketplace |

Each hub lists its decks in reading order with a description of each. The sections below keep a short entry for
every deck, so older links to this page still find them.

---

## Software Engineering

**CI/CD, GitHub and deployment** now have their own hub, **[CI/CD &amp; DevOps](https://brendanjameslynskey.github.io/SW_Hub_CI_CD_DevOps/)**: [Introduction to CI/CD](https://github.com/BrendanJamesLynskey/Introduction_to_CI_CD) · [Introduction to Jenkins](https://github.com/BrendanJamesLynskey/Introduction_to_Jenkins) · [Introduction to GitHub Actions](https://github.com/BrendanJamesLynskey/Introduction_to_GitHub_Actions) · [Introduction to GitHub](https://brendanjameslynskey.github.io/Introduction_to_GitHub/) · [Deploying Web Applications](https://brendanjameslynskey.github.io/Deploying_Web_Applications/) · [Deploying with Docker](https://brendanjameslynskey.github.io/Deploying_with_Docker/) · [Deploying Node.js Microservices](https://brendanjameslynskey.github.io/Deploying_Node_Microservices/).

| Project | Description |
| --- | --- |
| [Introduction to Databases](https://github.com/BrendanJamesLynskey/Introduction_to_Databases) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_Databases/blob/main/presentation.md)) | Slide deck covering relational theory, SQL, transactions, indexing, NoSQL models, and choosing the right database engine |
| [Introduction to Node.js](https://brendanjameslynskey.github.io/Introduction_to_Node_js/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_Node_js/blob/main/presentation.md)) | Interactive presentation on Node.js — V8 engine, event loop, async I/O, streams, Express middleware, npm, security, and scaling to production |
| [Introduction to VSCode Extensions](https://brendanjameslynskey.github.io/Introduction_to_VSCode_Extensions/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_VSCode_Extensions/blob/main/presentation.md)) | Interactive presentation on VSCode extensions — Extension API, Language Server Protocol, Webviews, testing, packaging, publishing, and CI/CD |
| [Writing VS Code Extensions — Tutorial Series](https://brendanjameslynskey.github.io/Writing_VSCode_Extensions/) ([repo](https://github.com/BrendanJamesLynskey/Writing_VSCode_Extensions)) | Step-by-step five-part tutorial on building VS Code extensions — (1) getting started & scaffolding with `yo code`, (2) commands & contribution points, (3) the Extension API in depth, (4) webviews & language features (Tree Views, Webviews, IntelliSense, diagnostics, LSP), (5) testing, packaging & publishing to the Marketplace and Open VSX. Hub landing page + five interactive decks |
| [Monetising & Distributing Software](https://brendanjameslynskey.github.io/Monetising_and_Distributing_Software/) ([md](https://github.com/BrendanJamesLynskey/Monetising_and_Distributing_Software/blob/main/presentation.md)) | Interactive presentation on turning code into a product — SaaS, licensing, Stripe integration, app stores, and scaling from free to paid |
| [tmux with Claude Code](https://brendanjameslynskey.github.io/TMUX_with_Claude_Code/) ([md](https://github.com/BrendanJamesLynskey/TMUX_with_Claude_Code/blob/main/presentation.md)) | Interactive presentation on tmux — terminal multiplexing, session management, pane workflows, and optimal use with Claude Code |
| [Introduction to Simulation](https://github.com/BrendanJamesLynskey/Introduction_to_Simulation) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_Simulation/blob/main/presentation.md)) | Interactive presentation on simulation across engineering — field solvers, SPICE, event-driven and cycle-based RTL, architecture and system models, Monte Carlo, virtual platforms, stiffness and step control, co-simulation, digital twins and verification and validation — with an interactive four-solver demo, measured simulator speeds, and links into every simulation series here |
| [Simulation Engineering Toolkit](https://brendanjameslynskey.github.io/SimEng_Hub_Toolkit/) ([repo](https://github.com/BrendanJamesLynskey/SimEng_Hub_Toolkit)) | Fourteen interactive decks on the engineering around a performance simulator — Rust for simulation engineers and a bit-exact PyO3 port, C++/SystemC TLM-2.0 models, DRAM/HBM memory modelling, a cocotb/Verilator verification bridge, testing frameworks, **Jenkins** (real runs of five simulator repos), **Jira and engineering metrics** (JQL checked against Atlassian's docs), **specifications, requirements and test plans** (EARS, a generated traceability matrix), **PyTorch and ONNX front ends**, **performance analysis** (py-spy flame graphs, cachegrind, regression gates from measured noise), and **measurement tools and methods** (a catalogue of every profiler, counter, energy and trace tool, coverage tool and architecture estimator the series uses, with measured overheads and a CACTI SRAM sweep), and **power, performance and area** (an area, yield and cost model for an FHE accelerator, a live Pareto-front explorer, and the trade-offs the series make, named), and **an accelerator model in SimPy, end to end** (a torch.export or ONNX graph through memory, DMA, buffer and compute-array models, with stall attribution, timelines, a cycle-stepped twin, a bit-identical C++/pybind11 fast path and an NTT workload). Every number from a recorded run; a glossary links each concept to its slide |
| [Rust_DES_Kernel](https://github.com/BrendanJamesLynskey/Rust_DES_Kernel) | A discrete-event simulation kernel in Rust and a bit-exact port of a SimPy LLM-serving simulator, exposed to Python with PyO3/maturin — differential, golden, property-based (proptest, Hypothesis) and mutation tests (95% score), 97.5% line coverage, 71–74× faster than SimPy; GitHub Actions and a Jenkins pipeline with JUnit, coverage and a performance gate |
| [Torch_Sim_Frontend](https://github.com/BrendanJamesLynskey/Torch_Sim_Frontend) | PyTorch and ONNX front ends for an accelerator cost model — a dispatch trace on the meta device or under fake tensors, torch.export, a torch.compile backend and a weightless ONNX graph walk, all agreeing exactly on Llama-3-8B; traces Llama-3-70B with no weights; roofline and offload cost models, operator coverage by operators, FLOPs and time; a **SimPy accelerator model** run end to end from the graph (memory, interconnect, DMA, on-chip buffer with back-pressure, compute array and vector unit; utilisation, stall and hot-spot reports, timeline plots), a bit-identical C++20/pybind11 fast path, a cycle-stepped twin, an NTT workload and ONNX Runtime execution-provider partitioning; an EARS specification with a generated traceability matrix; GitHub Actions and Jenkins |
| [MCP Gateway Playground](https://github.com/BrendanJamesLynskey/MCP_Gateway_Playground) | Docker MCP Gateway demo — custom MCP servers for tools, resources, and prompts behind a gateway, with a web-based client UI |
| [MCP Supergateway Playground](https://github.com/BrendanJamesLynskey/MCP_Supergateway_Playground) | MCP playground using supergateway — three MCP servers with SSE bridge, web UI, and CLI control for Claude Code mobile |
| [transformer-explainer](https://github.com/BrendanJamesLynskey/transformer-explainer) ([live](https://transformer-decoder-explained.vercel.app/) · [slides](https://brendanjameslynskey.github.io/transformer-explainer/) · [PDF](https://github.com/BrendanJamesLynskey/transformer-explainer/blob/main/docs/reports/backend-tour.pdf)) | Full-stack reference project — Next.js 14 App Router, TypeScript strict, Drizzle + Neon Postgres, Auth.js v5 GitHub OAuth, MDX content, D3 visualisations, Vitest + Playwright + axe-core. Built as a teaching artefact: the content is an interactive Transformer-decoder explainer; the codebase is a clean walked-through example of every layer (Server Components, Route Handlers, the graceful-fallback pattern, monotonic SQL upserts, token-bucket rate limiting, end-to-end OAuth, the test pyramid, CI/CD, Vercel deploy). 8-page backend-engineering PDF tour and a Reveal.js presentation included |

## Identity & Authorisation — Start Here

### [Open the Identity &amp; Authorisation Series](https://brendanjameslynskey.github.io/SW_Hub_Identity_Authorisation/)

Eleven decks in one reading order: the primer, then **Identity &amp; Access** (who is the user, and how do they
prove it to other systems?), then **Authorisation** (what may they, or their workload, do?). The hub has a
description of every deck.

Start with the series primer: [Identity & Authorisation — A Primer](https://brendanjameslynskey.github.io/Identity_and_Authorisation_Primer/).

## Identity & Access

Seven decks on *who is the user*: authentication primitives, then the federation stacks (OAuth, OIDC,
SAML/SCIM) that carry identity. Descriptions are on the [hub](https://brendanjameslynskey.github.io/SW_Hub_Identity_Authorisation/#part-identity-access).

### Pedagogical reading order

1. **[Authentication Methods](https://brendanjameslynskey.github.io/Authentication_Methods/)** — start here for "who is the user".
2. **[OAuth — A Gentle Primer](https://brendanjameslynskey.github.io/OAuth_Primer/)** — the conceptual warm-up for delegation.
3. **[Introduction to OAuth](https://brendanjameslynskey.github.io/Introduction_to_OAuth/)** — the OAuth 2.0/2.1 protocol in detail.
4. **[OAuth for MCP Servers](https://brendanjameslynskey.github.io/OAuth_for_MCP/)** — applied OAuth for the Model Context Protocol.
5. **[Introduction to OpenID Connect](https://brendanjameslynskey.github.io/Introduction_to_OpenID_Connect/)** — identity tokens on top of OAuth.
6. **[Advanced OpenID Connect](https://brendanjameslynskey.github.io/Advanced_OpenID_Connect/)** — FAPI 2.0, Federation 1.0, the EUDI wallet stack.
7. **[SAML 2.0 & SCIM](https://brendanjameslynskey.github.io/SAML_and_SCIM/)** — the parallel enterprise federation stack.

## Authorisation

Three decks on *what may the user (or workload) do, and how do we enforce it?* Descriptions are on the
[hub](https://brendanjameslynskey.github.io/SW_Hub_Identity_Authorisation/#part-authorisation).

### Pedagogical reading order

1. **[Authorization Models](https://brendanjameslynskey.github.io/Authorization_Models/)** — the conceptual foundations (RBAC / ABAC / ReBAC, Policy-as-Code).
2. **[Workload Identity & Service-Mesh AuthZ](https://brendanjameslynskey.github.io/Workload_Identity_AuthZ/)** — east-west service-to-service.
3. **[Edge & Gateway AuthZ](https://brendanjameslynskey.github.io/Edge_and_Gateway_AuthZ/)** — north-south, before the request reaches your code.

## Cloud Service Models (`*aaS`)

A six-deck consolidated treatment of cloud service models — IaaS / PaaS / SaaS / CaaS / FaaS / AIaaS — with deep coverage of architecture, deployment, security and the LLM-as-a-Service landscape. Companion to the deployment and Docker decks in the [CI/CD &amp; DevOps hub](https://brendanjameslynskey.github.io/SW_Hub_CI_CD_DevOps/) and the Monetising deck above; new content is the architectural and operational depth (multi-tenancy, IAM, compliance, managed AI) those decks deliberately don't cover.

| Project | Description |
| --- | --- |
| [Cloud `*aaS` Hub](https://github.com/BrendanJamesLynskey/Cloud_aaS_Hub) | Series index — links to all six decks plus related existing material |
| [Cloud `*aaS` 01 — Service Models](https://brendanjameslynskey.github.io/Cloud_aaS_01_Service_Models/) ([repo](https://github.com/BrendanJamesLynskey/Cloud_aaS_01_Service_Models)) | The *aaS taxonomy — IaaS / PaaS / SaaS / CaaS / FaaS / AIaaS, the shared-responsibility model, 1999 → 2026 history, pricing models, vendor matrix, when to use what |
| [Cloud `*aaS` 02 — IaaS Foundations](https://brendanjameslynskey.github.io/Cloud_aaS_02_IaaS_Foundations/) ([repo](https://github.com/BrendanJamesLynskey/Cloud_aaS_02_IaaS_Foundations)) | Compute (VMs, spot, bare metal), networking (VPC, subnets, peering, Transit Gateway, PrivateLink), storage (block / object / file), regions &amp; AZs, identity primitives, when IaaS still wins |
| [Cloud `*aaS` 03 — PaaS / FaaS / CaaS](https://brendanjameslynskey.github.io/Cloud_aaS_03_PaaS_FaaS_CaaS/) ([repo](https://github.com/BrendanJamesLynskey/Cloud_aaS_03_PaaS_FaaS_CaaS)) | Heroku / Render / Fly / Vercel / App Engine · Lambda / Cloud Functions / Workers · Cloud Run / ECS Fargate / Container Apps · managed Kubernetes (EKS / GKE / AKS) · cold starts, latency, pricing, decision matrix |
| [Cloud `*aaS` 04 — SaaS Architecture](https://brendanjameslynskey.github.io/Cloud_aaS_04_SaaS_Architecture/) ([repo](https://github.com/BrendanJamesLynskey/Cloud_aaS_04_SaaS_Architecture)) | Multi-tenancy patterns (silo / pool / bridge / hybrid), tenant isolation (RLS), B2B identity (SAML / OIDC / SCIM), Auth-as-a-Service providers, metering &amp; billing data model, per-tenant observability, residency, cell-based architecture |
| [Cloud `*aaS` 05 — Cloud Security](https://brendanjameslynskey.github.io/Cloud_aaS_05_Cloud_Security/) ([repo](https://github.com/BrendanJamesLynskey/Cloud_aaS_05_Cloud_Security)) | Shared-responsibility deep dive · IAM across AWS / GCP / Azure (STS, federation, OIDC) · secrets (KMS / HSM / Vault) · network security (PrivateLink, mTLS, zero trust) · encryption (at rest / in transit / in use, confidential compute) · compliance (SOC 2 / ISO / HIPAA / GDPR / PCI / FedRAMP / EU AI Act / DORA) · supply chain (SBOM, SLSA, Sigstore) · real incidents |
| [Cloud `*aaS` 06 — LLM-as-a-Service](https://brendanjameslynskey.github.io/Cloud_aaS_06_LLM_aaS/) ([repo](https://github.com/BrendanJamesLynskey/Cloud_aaS_06_LLM_aaS)) | OpenAI / Anthropic / Google / Bedrock / Vertex / Azure OpenAI / Together / Groq / Fireworks / Replicate · pricing &amp; latency · prompt caching · embeddings &amp; RAG-as-a-Service · agents-as-a-Service · fine-tuning APIs · evals / observability / guardrails · MCP server hosting · LLM-specific security · cost engineering |

## Web Development

### [Open the Web Development Series](https://brendanjameslynskey.github.io/SW_Hub_Web_Development/)

Twenty-five decks in six parts, from the browser platform up to the server and its data. The hub has the reading
order and a description of every deck; Introduction to Node.js is listed under Software Engineering above as well.

- **The platform:** [CSS Layout](https://brendanjameslynskey.github.io/Introduction_to_CSS_Layout/) · [TypeScript](https://brendanjameslynskey.github.io/Introduction_to_TypeScript/) · [Web Workers](https://brendanjameslynskey.github.io/Introduction_to_Web_Workers/) · [WebSockets](https://brendanjameslynskey.github.io/Introduction_to_WebSockets/) · [Server-Sent Events](https://brendanjameslynskey.github.io/Introduction_to_Server_Sent_Events/)
- **Front-end frameworks:** [React](https://brendanjameslynskey.github.io/Introduction_to_React/) · [Angular](https://brendanjameslynskey.github.io/Introduction_to_Angular/) · [Next.js](https://brendanjameslynskey.github.io/Introduction_to_Next_js/)
- **Node.js and Express:** [Node.js](https://brendanjameslynskey.github.io/Introduction_to_Node_js/) · [Express.js](https://brendanjameslynskey.github.io/Introduction_to_Express_js/) · [Express Middleware](https://brendanjameslynskey.github.io/Introduction_to_Express_Middleware/) · [Express in Practice](https://brendanjameslynskey.github.io/Express_in_Practice/) · [REST API Design](https://brendanjameslynskey.github.io/Introduction_to_REST_API_Design/) · [GraphQL](https://brendanjameslynskey.github.io/Introduction_to_GraphQL/)
- **Server-side templating:** [Server-Side Templating](https://brendanjameslynskey.github.io/Introduction_to_Server_Side_Templating/) · [EJS](https://brendanjameslynskey.github.io/Introduction_to_EJS/) · [Pug](https://brendanjameslynskey.github.io/Introduction_to_Pug/) · [Handlebars](https://brendanjameslynskey.github.io/Introduction_to_Handlebars/)
- **Authentication and data:** [Web Authentication](https://brendanjameslynskey.github.io/Introduction_to_Web_Authentication/) · [Passport.js](https://brendanjameslynskey.github.io/Introduction_to_Passport_js/) · [Node.js & Databases](https://brendanjameslynskey.github.io/Introduction_to_Node_Databases/) · [Knex](https://brendanjameslynskey.github.io/Introduction_to_Knex/)
- **Python, testing and tools:** [FastAPI](https://brendanjameslynskey.github.io/Introduction_to_FastAPI/) · [Testing Web Applications](https://brendanjameslynskey.github.io/Introduction_to_Testing_Web_Applications/) · [Reveal.js](https://brendanjameslynskey.github.io/Introduction_to_Reveal_js/)

## Algorithms

### [Open the Algorithms &amp; Data Structures Series](https://brendanjameslynskey.github.io/SW_Hub_Algorithms_Data_Structures/)

Twenty-four decks in one reading order: complexity first, then the data structures, then the algorithms that use
them, with a coding gym to practise on. Descriptions are on the hub.

[Computational Complexity](https://brendanjameslynskey.github.io/Computational_Complexity/) · [Sorting Algorithms](https://brendanjameslynskey.github.io/Sorting_Algorithms/) · [Divide and Conquer](https://brendanjameslynskey.github.io/Divide_and_Conquer/) · [Hashing Algorithms](https://brendanjameslynskey.github.io/Hashing_Algorithms/) · [String Matching Algorithms](https://brendanjameslynskey.github.io/String_Matching_Algorithms/) · [Greedy Algorithms](https://brendanjameslynskey.github.io/Greedy_Algorithms/) · [Dynamic Programming](https://brendanjameslynskey.github.io/Dynamic_Programming/) · [Backtracking Algorithms](https://brendanjameslynskey.github.io/Backtracking_Algorithms/) · [Graph Algorithms](https://brendanjameslynskey.github.io/Graph_Algorithms/) · [Shortest Path Algorithms](https://brendanjameslynskey.github.io/Shortest_Path_Algorithms/) · [Minimum Spanning Trees](https://brendanjameslynskey.github.io/Minimum_Spanning_Trees/) · [Network Flow Algorithms](https://brendanjameslynskey.github.io/Network_Flow_Algorithms/)

## Data Structures

Twelve decks, part 2 of the [Algorithms &amp; Data Structures series](https://brendanjameslynskey.github.io/SW_Hub_Algorithms_Data_Structures/#part-data-structures):

[Arrays and Linked Lists](https://brendanjameslynskey.github.io/Arrays_and_Linked_Lists/) · [Stacks and Queues](https://brendanjameslynskey.github.io/Stacks_and_Queues/) · [Hash Tables](https://brendanjameslynskey.github.io/Hash_Tables/) · [Binary Trees](https://brendanjameslynskey.github.io/Binary_Trees/) · [Binary Search Trees](https://brendanjameslynskey.github.io/Binary_Search_Trees/) · [Balanced Trees](https://brendanjameslynskey.github.io/Balanced_Trees/) · [B-Trees](https://brendanjameslynskey.github.io/B_Trees/) · [Heaps and Priority Queues](https://brendanjameslynskey.github.io/Heaps_and_Priority_Queues/) · [Tries](https://brendanjameslynskey.github.io/Tries/) · [Graph Data Structures](https://brendanjameslynskey.github.io/Graph_Data_Structures/) · [Disjoint Sets (Union-Find)](https://brendanjameslynskey.github.io/Disjoint_Sets_Union_Find/) · [Bloom Filters & Probabilistic DS](https://brendanjameslynskey.github.io/Bloom_Filters_and_Probabilistic_DS/)

## Coding Practice

Part 4 of the [Algorithms &amp; Data Structures series](https://brendanjameslynskey.github.io/SW_Hub_Algorithms_Data_Structures/#part-practice).

| Project | Description |
| --- | --- |
| [Coding Challenge Coach](https://github.com/BrendanJamesLynskey/Coding_Challenge_Coach) ([prompt](https://github.com/BrendanJamesLynskey/Coding_Challenge_Coach/blob/main/prompts/portable_examiner.md)) | LLM-examined, LeetCode-style coding practice for rebuilding hand-coding skill — 860 problems in **Python, C, JavaScript, TypeScript, Verilog, SystemVerilog and VHDL** across DSA, Modern Python (asyncio, concurrency, typing), Data & SQL, DSP, numerical, AI/ML, LangChain/LangGraph, web/FastAPI, embedded C and digital design. Per-language levels start at easy-only Warm-up; `/challenge`, `/hint`, `/grade`, `/solution` slash commands; reference-verified tests with Accepted / Wrong Answer / TLE verdicts; hidden tests + 100-point rubric at grading; real OpenAI / Gemini / OpenRouter calls to low-cost models plus a deterministic fake-LLM server; Binary Chop worked in all seven languages; Claude never writes your code (examiner-mode CLAUDE.md + hook) |

## Compilers

A ten-deck consolidated series on **compiler construction** — how source text becomes running code. From the history of the field and the classic pipeline, through the front end (lexing, parsing, semantic analysis & type systems), the middle end (intermediate representations, SSA, optimisation), the back end (code generation), and runtimes (JITs, GC, WebAssembly), ending by building a small compiler end to end. Each deck is a self-contained Reveal.js presentation with hand-authored inline-SVG diagrams and copy-and-run code, plus a Markdown companion.

### Pedagogical reading order

1. **A History of Compilers** — the field, 1950s → today.
2. **The Compiler Pipeline** — the architecture that frames everything below.
3–5. **Front end** — Lexical Analysis → Syntax Analysis → Semantic Analysis & Type Systems.
6–7. **Middle end** — Intermediate Representations → Optimization.
8. **Back end** — Code Generation.
9. **Runtime** — Runtimes, JITs & Modern Backends.
10. **Capstone** — Building a Mini-Compiler, end to end.

| Project | Description |
| --- | --- |
| [Compilers — Series Hub](https://brendanjameslynskey.github.io/Compilers/) ([repo](https://github.com/BrendanJamesLynskey/Compilers)) | Series index & landing page — links to all ten decks, the pipeline-at-a-glance diagram, and the learning arc (front end → middle end → back end → runtime → capstone) |
| [01 — A History of Compilers](https://brendanjameslynskey.github.io/Compilers/01_History_of_Compilers/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/01_History_of_Compilers/presentation.md)) | First assemblers (Booth, Wheeler), Hopper's A-0 & the word "compiler", FORTRAN's optimiser, ALGOL & BNF, the Chomsky hierarchy, LR/LALR parsing, lex & yacc, the Dragon Book, GCC, SSA, the JIT lineage (Self → HotSpot), LLVM, and the modern infrastructure era (Wasm, MLIR) |
| [02 — The Compiler Pipeline](https://brendanjameslynskey.github.io/Compilers/02_The_Compiler_Pipeline/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/02_The_Compiler_Pipeline/presentation.md)) | Compiler vs interpreter vs JIT, analysis vs synthesis, the phases end to end, a worked trace of one statement through every stage, front/middle/back ends and the N×M "narrow waist", the full toolchain, bootstrapping & T-diagrams, cross-compilation |
| [03 — Lexical Analysis](https://brendanjameslynskey.github.io/Compilers/03_Lexical_Analysis/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/03_Lexical_Analysis/presentation.md)) | Regular expressions & regular languages, NFA vs DFA, Thompson's construction, the subset construction & DFA minimisation, maximal munch & lookahead, hand-written vs generated scanners (lex/flex/re2c), literals & Unicode, the Python INDENT/DEDENT and C lexer-hack cases |
| [04 — Syntax Analysis (Parsing)](https://brendanjameslynskey.github.io/Compilers/04_Syntax_Analysis/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/04_Syntax_Analysis/presentation.md)) | Context-free grammars, derivations, parse trees vs ASTs, ambiguity & precedence; top-down (recursive descent, FIRST/FOLLOW, LL(1), Pratt parsing); bottom-up (shift-reduce, LR(0) items, SLR/LALR(1)); conflicts; generators (yacc/bison, ANTLR, tree-sitter, PEG); error recovery |
| [05 — Semantic Analysis & Type Systems](https://brendanjameslynskey.github.io/Compilers/05_Semantic_Analysis_and_Types/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/05_Semantic_Analysis_and_Types/presentation.md)) | Symbol tables & scope, name resolution & shadowing, attribute grammars & syntax-directed translation, type-system axes, typing judgements (Γ ⊢ e : τ), Hindley–Milner inference & unification, subtyping & variance, generics & type classes, diagnostics |
| [06 — Intermediate Representations](https://brendanjameslynskey.github.io/Compilers/06_Intermediate_Representations/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/06_Intermediate_Representations/presentation.md)) | Why an IR, the HIR/MIR/LIR spectrum, three-address code, stack vs register bytecode (JVM/CPython/Wasm vs Lua/Dalvik), control-flow graphs, dominators, SSA & φ-functions (construction & destruction), LLVM IR in depth, CPS, sea-of-nodes, MLIR |
| [07 — Optimization](https://brendanjameslynskey.github.io/Compilers/07_Optimization/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/07_Optimization/presentation.md)) | The "as-if" rule, scope levels up to LTO & PGO, the data-flow framework (lattices, transfer functions, fixed points), the four classic analyses, classic transforms (CSE, DCE, inlining, strength reduction), loop optimisations & vectorisation, SSA-based passes (SCCP, GVN), alias analysis, phase ordering |
| [08 — Code Generation](https://brendanjameslynskey.github.io/Compilers/08_Code_Generation/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/08_Code_Generation/presentation.md)) | The three interacting subproblems; instruction selection (tree tiling, BURS, SelectionDAG/GlobalISel); register allocation (interference graphs, graph colouring, Chaitin–Briggs, linear scan, coalescing); instruction scheduling; the System V AMD64 ABI, stack frames & prologue/epilogue; a worked x86-64 / AArch64 example |
| [09 — Runtimes, JITs & Modern Backends](https://brendanjameslynskey.github.io/Compilers/09_Runtime_JIT_and_Backends/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/09_Runtime_JIT_and_Backends/presentation.md)) | Interpreters & dispatch (threaded code, computed goto), JITs (baseline vs optimising, tracing, tiered execution in V8/HotSpot), inline caches, deoptimisation & OSR, garbage collection (generational, concurrent), exception handling, dynamic linking (PLT/GOT), and modern backends: LLVM, Cranelift, GraalVM, MLIR, WebAssembly |
| [10 — Building a Mini-Compiler](https://brendanjameslynskey.github.io/Compilers/10_Building_a_Mini_Compiler/) ([md](https://github.com/BrendanJamesLynskey/Compilers/blob/main/10_Building_a_Mini_Compiler/presentation.md)) | Capstone — one tiny language ("MiniLang") threaded through the whole pipeline in real, runnable code: grammar → hand-written lexer → recursive-descent + Pratt parser → type checker → three-address IR → constant folding & DCE → stack-VM bytecode → an interpreter that runs it — plus testing, error messages, and where to go next |

## Docker

Nine Docker decks, part 2 of the [CI/CD &amp; DevOps series](https://brendanjameslynskey.github.io/SW_Hub_CI_CD_DevOps/#part-containers) (after Deploying with
Docker), where each has a description:

[Docker Networking](https://brendanjameslynskey.github.io/Docker_Networking/) · [Docker Volumes & Storage](https://brendanjameslynskey.github.io/Docker_Volumes_and_Storage/) · [Docker Compose in Depth](https://brendanjameslynskey.github.io/Docker_Compose_in_Depth/) · [Docker Multi-Stage Builds](https://brendanjameslynskey.github.io/Docker_Multi_Stage_Builds/) · [Docker Security](https://brendanjameslynskey.github.io/Docker_Security/) · [Docker for CI/CD](https://brendanjameslynskey.github.io/Docker_for_CI_CD/) · [Docker Troubleshooting](https://brendanjameslynskey.github.io/Docker_Troubleshooting/) · [Docker Swarm & Orchestration](https://brendanjameslynskey.github.io/Docker_Swarm_and_Orchestration/) · [Docker for LLMs, Agents & MCP](https://brendanjameslynskey.github.io/Docker_for_LLMs_and_Agents/)

## Python Tooling

| Project | Description |
| --- | --- |
| [Introduction to uv](https://brendanjameslynskey.github.io/Introduction_to_uv/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_uv/blob/main/presentation.md)) | Interactive presentation on **uv** — Astral's Rust-based all-in-one Python package & project manager. Installation, `uv pip` drop-in, projects & `uv.lock`, `uv sync` & `uv run`, Python version management, PEP 723 inline scripts, `uvx` tools, workspaces, build & publish, performance internals, migration from pip-tools and Poetry, CI patterns |
| [uv in Practice](https://brendanjameslynskey.github.io/uv_in_Practice/) ([md](https://github.com/BrendanJamesLynskey/uv_in_Practice/blob/main/presentation.md)) | Companion deck of production recipes for uv — Dockerfile patterns, multi-stage distroless images, BuildKit cache mounts, GitHub Actions / GitLab CI / Jenkins / Buildkite, pre-commit hooks, monorepo workspaces, private indexes, reproducibility & SBOM, PEP 723 scripts at scale, PyTorch + CUDA wheel selection, conda/mamba interop, Poetry → uv migration playbook, troubleshooting |
| [Introduction to Poetry](https://brendanjameslynskey.github.io/Introduction_to_Poetry/) ([md](https://github.com/BrendanJamesLynskey/Introduction_to_Poetry/blob/main/presentation.md)) | Interactive presentation on **Poetry** — the opinionated Python dependency manager & build backend. Installation, `poetry new` / `init`, `pyproject.toml` in the Poetry 2.0 / PEP 621 era, `poetry add` / `remove`, hash-pinned `poetry.lock`, `install` & `sync`, `poetry env` & in-project venvs, dependency groups vs extras, private indexes & source priorities, build & publish via `poetry-core`, plugins (export, bundle, poethepoet), Mixology resolver internals, comparison with pip / pipenv / pdm / Hatch / uv, migration from `requirements.txt`, Poetry 1.x → 2.0 migration, CI & Docker patterns |

---
