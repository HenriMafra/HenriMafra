# Henri Mafra

Computer science, low-level systems, and security research.

```text
[    0.000000] Linux version 6.10.x-henri (x86_64) (gcc 14.1) #1 SMP PREEMPT
[    0.000010] Initializing Henri Mafra runtime environment...
[    0.000140] Command line: target=systems_engineering,low_level_security,data_infrastructure
[    0.001020] CPU0: Core systems online: Concurrency, IPC, Memory Management
[    0.001850] I/O: Data layers active: PostgreSQL, Supabase, Cloudflare Edge Runtimes
[    0.002400] Net: WebSockets, REST, Model Context Protocol (MCP) daemon mounted
[    0.003110] Status: Operational. Running active workloads and low-level exploit research.
```

### Current Production Stack (What I Use)

| Layer | Technologies | Practical Usage |
| :--- | :--- | :--- |
| **Languages** | Python, TypeScript, JavaScript, SQL, PowerShell | System scripting, pipeline automation, tooling |
| **Data & Storage** | PostgreSQL, Supabase, Pandas, NumPy | Relational modeling, API data ingestion, wrangling |
| **Edge & Cloud** | Cloudflare Workers, REST, Docker | Serverless compute, distributed edge workers, containers |
| **Protocols & Systems** | WebSockets, Discord IPC, Manifest V3 Extensions | Process communication, browser instrumentation |
| **CI/CD & DevOps** | GitHub Actions, Git, Linux | Automated testing, deployment pipelines, scheduled jobs |

<br>

<div align="center">
  <img src="giphy.gif" width="600px" alt="Henri Mafra">
</div>

<br>

### Systems & Exploit Engineering Roadmap (What I Am Learning)

Technical progression based on systems programming, memory safety bypasses, and browser internals:

| Phase | Specialization | Core Focus & Reference Study |
| :--- | :--- | :--- |
| **Phase I** | **Silicon Substrate & OS Internals** | Computer architecture (Wentzlaff), pure C and bitwise operations, manual memory allocation (malloc/free internals), virtual memory and address spaces (OSTEP: paging, TLB, syscalls), x86_64 assembly, static disassembly with Ghidra and dynamic debugging with GDB/GEF. |
| **Phase II** | **Binary Exploitation & Heap Internals** | Stack buffer overflows, position-independent shellcoding, Return-Oriented Programming (ROP chains to bypass DEP/NX), glibc malloc architecture (chunks, tcache poisoning, fastbins, Use-After-Free), timing side-channel attacks, and automated coverage-guided fuzzing with AFL++ and ASan. |
| **Phase III** | **Browser Security & V8 JIT Architecture** | Compiler theory (AST, Intermediate Representations, bounds check elimination), modern C++ object layout (vtables, dynamic casting, RAII), Chromium multi-process isolation, V8 internals (Ignition bytecode interpreter, TurboFan JIT compiler, type confusion vulnerabilities, addrof/fakeobj memory primitives, and Mojo IPC sandbox escapes). |
| **Phase 0** | **High-Throughput Data Infrastructure** | Code-first data transformations, dbt Core dimensional models and automated testing, DuckDB in-memory analytical queries on Apache Parquet, Medallion architecture (Bronze, Silver, Gold), and zero-GUI cron pipelines. |

<br>

### Selected Repositories

| Repository | Function | Architecture |
| :--- | :--- | :--- |
| [prime-discord-presence](https://github.com/HenriMafra/prime-discord-presence) | Real-time browser media state sync to Discord IPC. | JavaScript, WebSockets, Discord RPC, Manifest V3 |
| [Cuidamed](https://github.com/HenriMafra/Cuidamed) | Clinical scheduling system with OpenFDA verification. | Python, Streamlit, PostgreSQL, Supabase, CI/CD |
| [Brazilian-Soccer-Database](https://github.com/HenriMafra/Brazilian-Soccer-Database) | Statistical analysis and predictive modeling for sports data. | Python, Pandas, NumPy, scikit-learn |

<br>

### Network & Contact

* GitHub: [@HenriMafra](https://github.com/HenriMafra)
* Web: [henrimafra.github.io](https://henrimafra.github.io/)
* Email: henri.afly@gmail.com
