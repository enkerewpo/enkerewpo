I build operating systems, in Rust and C.

I'm a PhD candidate at the **School of Computer Science, Peking University**, and a
researcher at the [Syswonder](https://github.com/syswonder) community. My work concerns
the systems layer beneath embodied intelligence: how an operating system should expose
heterogeneous robot hardware to LLM-driven agents as typed, discoverable, and composable
abstractions.

### Systems I build

**[Robonix](https://github.com/syswonder/robonix)** — an Embodied AI Operating System,
and the reference implementation of the EAIOS architecture. Robot functionality is
modelled as *capabilities* (typed interfaces) carrying *contracts*, supplied by
primitives, services, or skills, and resolved at runtime through a distributed registry.
Agent-generated plans compile into RTDL execution trees dispatched across processes and
machines. Deployed on 14+ robot platforms. → [robonix.ai](https://robonix.ai)

**[hvisor](https://github.com/syswonder/hvisor)** — a lightweight type-1 hypervisor in
Rust, providing static partitioning for edge devices across aarch64, riscv64, and
loongarch64. Maintainer since 2023. → [hvisor.syswonder.org](https://hvisor.syswonder.org)

### Upstream

**Linux kernel** — LoongArch KVM
([tracepoints](https://github.com/torvalds/linux/commit/36d09b96d3e79518e2be31fc7960cc694702afb8),
[fixes](https://github.com/torvalds/linux/commit/8b2d01fec800081dd68271c01e4d239ef4d7115e))
and [documentation tooling](https://github.com/torvalds/linux/commit/6b8edfcd661b569f077cc1ea1f7463ec38547779).

**[Asterinas](https://github.com/asterinas/asterinas)** — the `getcpu` syscall
([#1859](https://github.com/asterinas/asterinas/pull/1859)) and `/proc/version`
([#2679](https://github.com/asterinas/asterinas/pull/2679)).

**LoongArch64 enablement** across the Rust and systems ecosystem —
[unwinding](https://github.com/nbdd0121/unwinding/pull/50),
[LLVM](https://github.com/llvm/llvm-project/pull/128889),
[nixpkgs](https://github.com/NixOS/nixpkgs/pull/423765),
[Arch for LoongArch](https://github.com/lcpu-club/loongarch-packages/pull/759).

**[FreeBSD](https://www.freebsd.org)** — Simplified Chinese
[translation team](https://docs.freebsd.org/zh-cn), since 2024.

### Publications

Co-author, CCF Ubiquitous Operating Systems Open Community,
[*Embodied AI Operating System Technical White Paper*](https://gitlink.org.cn/zone/uos/source/292),
January 2026 — framing the OS as a unified substrate over the three logical spaces of
perception, cognition, and action.

### Elsewhere

I write game and electronic music
([SoundCloud](https://soundcloud.com/wheatfox) ·
[Spotify](https://open.spotify.com/artist/1u5SE8RW4ivt3LgZR7skkO) ·
[Bandcamp](https://wheatfox.bandcamp.com/)), keep an OS blog at
[oscommunity.cn](https://www.oscommunity.cn), and hack on Redox as
[wheatfox@redox-os](https://gitlab.redox-os.org/wheatfox).

Reach me at `yulonghan@stu.pku.edu.cn` · [ORCID](https://orcid.org/0009-0006-3482-9652)
