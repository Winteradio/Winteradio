# Wonmock Lee — Graphics & Engine Programmer

C++ graphics engineer at **Hyundai AutoEver**. After hours I build a game engine — and every library under it — from scratch, and measure what I build.

**Portfolio → [winteradio.github.io](https://winteradio.github.io/)** · tot4766@gmail.com · [LinkedIn](https://www.linkedin.com/in/wonmock-lee-642302216/) · [Blog](https://gong-si.tistory.com/)

## Highlights

- **1M instances, 5.4 → 22 FPS** — a month of profiling ([#25](https://github.com/Winteradio/Game-Engine/issues/25)): TRS moved to a GPU compute pass, a 2M-per-frame hash insert cut by a dirty guard.
- **The whole stack, not just the renderer** — a 4-thread engine (World · Render · RHI · Asset) on six in-house libraries: ECS, GC, reflection, STL-free containers, logging, build rules.
- **RHI for explicit APIs** — OpenGL 4.6 backend running; Vulkan backend with TLSF sub-allocated device memory, staging uploads and barriers in progress.
- **Finds bugs, then fixes them** — a full code review filed 26 bugs across five repos; 25 were fixed within six days. 424 commits, 146 PRs.
- **At work** — MVT map renderer architecture, style-batched VBOs (90%+ fewer draw calls), KTX/ASTC pipeline (70–80% faster loading), GPU skinning.

## Projects

| Repository | What it is |
|---|---|
| [Game-Engine](https://github.com/Winteradio/Game-Engine) | Multithreaded C++17 engine · deferred rendering · directional shadows · GL 4.6 / Vulkan RHI |
| [ECS-with-Scene-and-Node](https://github.com/Winteradio/ECS-with-Scene-and-Node) | Entity · Component · Node, system order from a dependency graph (Kahn) |
| [MemoryPool](https://github.com/Winteradio/MemoryPool) | Mark-and-sweep GC with a time-budgeted purge |
| [Reflection](https://github.com/Winteradio/Reflection) | `GENERATE` / `PROPERTY` / `METHOD` reflection with macros and templates only |
| [Container](https://github.com/Winteradio/Container) | STL-free containers — Robin Hood HashMap (1.72× faster inserts), TLSF allocator |
| [Log](https://github.com/Winteradio/Log) · [CMake](https://github.com/Winteradio/CMake) | Stream-style logger · shared build rules for every repo |

## Stack

![C++](https://img.shields.io/badge/C++-00599C.svg?&style=for-the-badge&logo=cplusplus&logoColor=white) ![OpenGL](https://img.shields.io/badge/OpenGL-5586A4.svg?&style=for-the-badge&logo=opengl&logoColor=white) ![Vulkan](https://img.shields.io/badge/Vulkan-AC162C.svg?&style=for-the-badge&logo=vulkan&logoColor=white) ![glTF](https://img.shields.io/badge/glTF-87C540.svg?&style=for-the-badge&logo=glTF&logoColor=white) ![CMake](https://img.shields.io/badge/CMake-064F8C.svg?&style=for-the-badge&logo=cmake&logoColor=white)

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=tot4766)](https://solved.ac/tot4766/)
