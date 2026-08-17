# Josh Schuler

### Reverse engineering · Native game ports · Engineering leadership

I reconstruct classic games as native C programs from disassembly, traces, and observed behavior—without embedding an emulator or distributing copyrighted game data. I bring 15+ years of software experience to the work, from architecture and delivery through implementation, verification, and release.

[Portfolio](https://schulerj89.github.io/github-page/) · [Native ports](#native-game-ports) · [Open-source contributions](#open-source)

## Native game ports

| Project | What is being reconstructed |
| --- | --- |
| [NBA All-Star Challenge](https://github.com/schulerj89/all-star-challenge-c-port) | Game Boy → native C/Win32. Bank-aware Ghidra analysis, ROM-derived asset packs, deterministic parity manifests, and playable One-on-One, Free Throws, H-O-R-S-E, Accuracy Shootout, and Tournament modes. |
| [Double Dribble](https://github.com/schulerj89/double-dribble-c-port) | NES → native C/Win32. Recovered title, audio, introduction, configuration, tip-off, possession, shooting, scoring, inbound, and free-throw behavior with trace-backed tests. |
| [Tecmo NBA Basketball](https://github.com/schulerj89/tecmo-basketball-port) | NES → native C/Win32. Playable preseason and season games, menus, presentation, court systems, team data, and a growing translation of the original CPU logic. |

These are source-level preservation projects. Each one separates public code from user-owned ROM data, imports only validated local assets, and documents what is exact, approximated, or still missing.

## How I work

- Recover banked assembly and data structures with Ghidra, emulator traces, and focused scripts.
- Translate behavior into legible C while preserving original state machines and fixed-point rules.
- Compare native output against reproducible reference captures and deterministic regressions.
- Keep legal and technical boundaries explicit: no ROMs, extracted assets, or embedded emulation.

## Open source

I also contribute upstream framework and documentation improvements:

- Laravel framework: [#53109](https://github.com/laravel/framework/pull/53109), [#53097](https://github.com/laravel/framework/pull/53097), [#43639](https://github.com/laravel/framework/pull/43639)
- PHP documentation: [#3135](https://github.com/php/doc-en/pull/3135)
- Laravel documentation: [#8123](https://github.com/laravel/docs/pull/8123)

## Beyond the ports

[Campus Gridiron Dynasty](https://github.com/schulerj89/campus-gridiron-dynasty) is a 20-season college-football simulation built with React and TypeScript. My broader work spans systems programming, browser games, developer tooling, Go, Rust, TypeScript, and applied AI.
