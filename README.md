## Yulong Han (wheatfox) 🦊

<a href="https://github.com/anuraghazra/github-readme-stats">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://my-readme-stats-snowy-sigma.vercel.app/api?username=enkerewpo&theme=dark&show_icons=true&hide_border=true">
  <img alt="GitHub Stats" src="https://my-readme-stats-snowy-sigma.vercel.app/api?username=enkerewpo&theme=default&show_icons=true&hide_border=true">
</picture>
</a>

<a href="https://github.com/syswonder/robonix">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://my-readme-stats-snowy-sigma.vercel.app/api/pin/?username=syswonder&repo=robonix&theme=dark&hide_border=true">
  <img alt="Robonix" src="https://my-readme-stats-snowy-sigma.vercel.app/api/pin/?username=syswonder&repo=robonix&theme=default&hide_border=true">
</picture>
</a>
<a href="https://github.com/syswonder/hvisor">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://my-readme-stats-snowy-sigma.vercel.app/api/pin/?username=syswonder&repo=hvisor&theme=dark&hide_border=true">
  <img alt="hvisor" src="https://my-readme-stats-snowy-sigma.vercel.app/api/pin/?username=syswonder&repo=hvisor&theme=default&hide_border=true">
</picture>
</a>

[![ORCID](https://img.shields.io/badge/ORCID-0009--0006--3482--9652-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0006-3482-9652)
[![Peking University](https://img.shields.io/badge/Peking%20University-PhD%20Student-C8102E?style=flat-square)](https://cs.pku.edu.cn)
[![Email](https://img.shields.io/badge/yulonghan@stu.pku.edu.cn-0A66C2?style=flat-square&logo=maildotru&logoColor=white)](mailto:yulonghan@stu.pku.edu.cn)

PhD student, **School of Computer Science, Peking University**.
Researcher at the [Syswonder](https://github.com/syswonder) community.

My work concerns the systems layer beneath embodied intelligence: how an operating system
should expose heterogeneous robot hardware to LLM-driven agents as typed, discoverable,
and composable abstractions — following the EAIOS architecture and its
primitive–service–skill–task abstraction hierarchy.

**Research interests** — embodied agent operating systems · agent systems ·
Rust operating systems · virtualization · heterogeneous hardware

---

### Publications

**《具身智能操作系统技术白皮书》** — *Embodied AI Operating System Technical White Paper*
*Co-author.* CCF Ubiquitous Operating Systems Open Community, January 2026.
Proposes the EAIOS design, positioning the operating system as a unified substrate over
the three logical spaces of **perception, cognition, and action**, structured by a
primitive–service–skill–task abstraction hierarchy. Robonix is its reference
implementation.
→ [gitlink.org.cn/zone/uos/source/292](https://gitlink.org.cn/zone/uos/source/292)

---

### Systems research and development

#### Robonix — Embodied AI Operating System (EAIOS)
*Lead developer.* The reference implementation of the EAIOS architecture. Robot
functionality is modelled as **capabilities** (typed interfaces) carrying **contracts**
(their shape), supplied by primitives, services, or skills, and resolved at runtime
through a distributed registry. Agent-generated task plans are compiled into RTDL
execution trees and dispatched across processes and machines, decoupling high-level
reasoning from the underlying robot embodiment. Deployed on 14+ robot platforms.
→ [github.com/syswonder/robonix](https://github.com/syswonder/robonix) · [robonix.ai](https://robonix.ai)

#### hvisor — Lightweight type-1 hypervisor in Rust
*Maintainer, 2023 – present.* A minimal bare-metal Type-1 hypervisor providing static
partitioning for edge devices, supporting **aarch64, riscv64, and loongarch64**.
→ [github.com/syswonder/hvisor](https://github.com/syswonder/hvisor) · [hvisor.syswonder.org](https://hvisor.syswonder.org)

#### Linux kernel — LoongArch KVM and documentation tooling
Upstream contributions to LoongArch virtualization and the kernel documentation toolchain:

- [`36d09b9`](https://github.com/torvalds/linux/commit/36d09b96d3e79518e2be31fc7960cc694702afb8) — LoongArch: KVM: Add tracepoints for CPUCFG and CSR emulation exits
- [`8b2d01f`](https://github.com/torvalds/linux/commit/8b2d01fec800081dd68271c01e4d239ef4d7115e) — LoongArch: KVM: Fix multiple typos of KVM code
- [`6b8edfc`](https://github.com/torvalds/linux/commit/6b8edfcd661b569f077cc1ea1f7463ec38547779) — docs: automarkup.py: Skip common English words as C identifiers

#### Asterinas — Linux-ABI-compatible framekernel in Rust
- [#1859](https://github.com/asterinas/asterinas/pull/1859) — Implement the `getcpu` syscall and its test application
- [#2679](https://github.com/asterinas/asterinas/pull/2679) — Add `/proc/version` support

#### LoongArch64 Rust and OS toolchain
Architecture enablement across the Rust and systems ecosystem:

- [nbdd0121/unwinding#50](https://github.com/nbdd0121/unwinding/pull/50) — LoongArch64 support in the Rust stack-unwinding library
- [llvm/llvm-project#128889](https://github.com/llvm/llvm-project/pull/128889) — `[mlir][Tosa]` unreachable case for bad Extension type
- [NixOS/nixpkgs#423765](https://github.com/NixOS/nixpkgs/pull/423765) — `ecc`: add LLVM to inputs, fixing a cross-compilation error
- [lcpu-club/loongarch-packages#759](https://github.com/lcpu-club/loongarch-packages/pull/759), [#779](https://github.com/lcpu-club/loongarch-packages/pull/779) — Arch Linux for LoongArch packaging
- Kernel and image support for hvisor guests:
  [linux-hvisor-loongarch64](https://github.com/enkerewpo/linux-hvisor-loongarch64) ·
  [buildroot-loongarch64](https://github.com/enkerewpo/buildroot-loongarch64) ·
  [baremetal-loongarch64-unwinding-test](https://github.com/enkerewpo/baremetal-loongarch64-unwinding-test)

#### Other open-source contributions
[FreeBSD](https://www.freebsd.org) — Simplified Chinese (zh_CN)
[translation team](https://docs.freebsd.org/zh-cn) member, 2024 – present ·
[Gleam](https://github.com/gleam-lang/gleam)
([#4082](https://github.com/gleam-lang/gleam/pull/4082),
[#4109](https://github.com/gleam-lang/gleam/pull/4109))

---

### Education

- **2024 – present** · PhD in Computer Science, Peking University
- **2020 – 2024** · BSc in Computer Science, Northwestern Polytechnical University

### Contact

`yulonghan@stu.pku.edu.cn` · `wheatfox17@icloud.com`
[OS blog](https://www.oscommunity.cn) ·
[ORCID](https://orcid.org/0009-0006-3482-9652) ·
[X](https://x.com/wheat_fox) ·
[Redox](https://gitlab.redox-os.org/wheatfox)

<sub>Outside systems work I write game and electronic music —
[SoundCloud](https://soundcloud.com/wheatfox) ·
[Spotify](https://open.spotify.com/artist/1u5SE8RW4ivt3LgZR7skkO) ·
[Bandcamp](https://wheatfox.bandcamp.com/)</sub>

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/enkerewpo/enkerewpo/refs/heads/master/profile-3d-contrib/profile-night-green.svg">
  <img alt="contribution graph" src="https://raw.githubusercontent.com/enkerewpo/enkerewpo/refs/heads/master/profile-3d-contrib/profile-green-animate.svg">
</picture>
