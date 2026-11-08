# Kaan Bartu Bozkurt

**Software Developer | Python Tooling, Testing & CI | Unreal Engine 5 Gameplay Systems**

I’m a Computer Engineering student building developer tools, investigating reproducible software failures, and developing systems-driven games. My approach is to understand the failure, make a focused change, and verify the result—without overstating what the tests prove.

**Core tools:** Python · pytest · Git / Git LFS · GitHub Actions · SQL / PostgreSQL · Celery · C++ · Unreal Engine 5 · Blueprints

[LinkedIn](https://www.linkedin.com/in/kaan-bartu-bozkurt-1b12b043b/) · [GitHub](https://github.com/kaanbartubozkurt)

## Selected engineering work

### Developer tools & backend

**[BranchRift — Git integration risk CLI](https://github.com/kaanbartubozkurt/branchrift)**
*Python · Git · Git LFS · CLI · CI*

A published, read-only tool that reports branch divergence, same-path changes, binary-sensitive collisions, Git LFS readiness and ownership/review gaps before integration. It provides evidence for a human decision; it does not merge branches or guarantee conflict prediction.
[PyPI package](https://pypi.org/project/branchrift/) · [Source code](https://github.com/kaanbartubozkurt/branchrift)

**[Nativory — React Native / Android upgrade evidence](https://github.com/kaanbartubozkurt/Nativory)**
*Python · Gradle · React Native · Evidence verification*

A conservative, read-only experiment for tracing native dependency and compatibility evidence. The current `main` branch supports a scoped AGP/Gradle check; additional Expo/FBJNI and ELF-alignment research remains in [draft PR #2](https://github.com/kaanbartubozkurt/Nativory/pull/2). It is not an APK certification or auto-repair tool.

**[Reprovant — Worker failure experiments](https://github.com/kaanbartubozkurt/reprovant)**
*Python · Celery · PostgreSQL · pytest*

Research into reproducible worker failure modes, including duplicate effects and state regressions. Includes controlled experiments and explicit evidence boundaries. **Research case study, not a commercially validated product or production certification.**
[Evidence case study](https://github.com/kaanbartubozkurt/reprovant/blob/main/docs/REPROVANT_EVIDENCE_CASE_STUDY.md)

### Gameplay engineering

**[False Normality — Psychological horror game](https://store.steampowered.com/app/4925070/)**
*Unreal Engine 5 · C++ · Blueprints · Gameplay systems*

Released on Steam on **September 15, 2026**. In our two-person team, I worked on gameplay logic, Blueprint systems, AI interactions and input behavior.

**[SON HAT — Supper's Ready / Civil Game Jam 2026](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/tree/integration/son-hat)**
*Unreal Engine 5.7 · C++ · Grappling · State-driven gameplay · Automation tests*

A **48-hour, unfinished game jam prototype** featuring grappling movement and a timed rooftop rescue-signaling system. My primary work covered C++ gameplay, rescue-state logic, HUD/interaction behavior, tests and integration. The source is available for technical review; the final city is **not reproducible as a standalone playable build** from the public repository.
[Gameplay C++](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/blob/integration/son-hat/Source/UEIntroProject_1/GrappleComponent.cpp) · [Rescue-state logic](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/blob/integration/son-hat/Source/UEIntroProject_1/SonHatEvacuationDirector.cpp) · [Verification limits](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/blob/integration/son-hat/README.md)

## Selected open-source contributions

- **[booth — PR #31](https://github.com/Vedantgitbot/booth/pull/31) · Merged.** Handled malformed AI model output without crashing, with regression tests; the maintainer verified the fix and merged it.
- **[newsT — PR #26](https://github.com/StefanOOEOrg/newsT/pull/26) · Merged.** Rejected non-finite sentiment scores (`NaN` / infinities), including numeric strings, with targeted regression coverage.
- **[Cura AI — PR #121](https://github.com/slealq/cura-ai/pull/121) · Open as of November 2, 2026.** Corrected all-failed image-batch outcomes and made provider errors and partial failures more visible. Local verification: **1,069 backend tests passed** and TypeScript checks passed; no live end-to-end deployment verification claimed.

## What I can help with

- Reproducing and fixing focused **Python / pytest / GitHub Actions CI** failures.
- Investigating **state, retry and data-integrity** bugs, with regression coverage.
- Building and debugging **Unreal Engine 5 C++ / Blueprint gameplay systems**.

I’m open to scoped freelance and contract work where the expected result and verification criteria are clear.

**Contact:** [LinkedIn](https://www.linkedin.com/in/kaan-bartu-bozkurt-1b12b043b/)
