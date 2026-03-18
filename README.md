# R2ND — Road to No Dependencies

An open ecosystem of tools, languages, and systems built from scratch.
No external dependencies. No vendor lock-in. 100% open source.

---

## What is R2ND?

R2ND is a long-term project to rebuild the software stack from the ground up —
language, standard library, UI, rendering, networking, and desktop environment —
as a single coherent ecosystem where every component is understood and controlled.

---

## The Stack

```
Applications
    └── R2ND Desktop        window manager, compositor, shell, native apps
        └── R2ND UI         hardware-accelerated UI rendering and layout
        └── 3D Renderer     custom graphics pipeline, no OpenGL wrappers
        └── Networking      TCP/UDP, HTTP, WebSocket — all internal
            └── Core Libraries   data structures, I/O, math, algorithms
                └── M++          compiled language, LLVM backend
                    └── OS
```

---

## Repositories

| Repository | Description | Status |
|---|---|---|
| [M++](https://github.com/mathiassol/mpp) | Low-level compiled language with LLVM backend | Active |
| [R2ND Website](https://github.com/mathiassol/r2nd-website) | Project website | Active |
| [R2ND UI](https://github.com/mathiassol/R2NDUI) | Custom UI rendering engine (R2ML markup, layout, rendering) | In Progress |
| [R2ND Platform](https://github.com/mathiassol/r2nd-platform) | Installer, CLI tools, and deployment scripts | In Progress |
| Core Libraries | Standard library — zero external dependencies | Planned |
| 3D Renderer | Graphics pipeline from scratch | Planned |
| R2ND Networking | Full networking stack (TCP/UDP, HTTP, WebSocket) | Planned |
| [R2ND Desktop](https://github.com/mathiassol/r2nd-desktop) | Complete desktop environment | In Progress |
| R2ND Tools | Build system, package manager, debugger | Planned |

> Repos without links are in local development and will be published when ready.

---

## M++ — The Language

M++ is the core language of the ecosystem. Everything is written in it.

```mpp
fn main() {
    let message = "Hello R2ND";
    print(message);
}
```

- Compiled via LLVM
- Manual memory management
- No garbage collector
- Designed to replace C/C++ within the ecosystem

→ **[View the M++ repo](https://github.com/mathiassol/mpp)**

---

## Philosophy

1. **No unnecessary dependencies** — every component is built here
2. **Full transparency** — all code is open and auditable
3. **Open ecosystem** — free to use, fork, and extend
4. **Developer freedom** — no lock-in, no telemetry, no forced upgrades
5. **Long-term maintainability** — built to last decades, not months

---

## Get Involved

This project is open source and contributions are welcome.
Each sub-project lives in its own repository — pick one and dive in.

---

> Built from scratch. Owned by everyone.
