# Kaan Bartu Bozkurt

**Software Developer | Python Tooling, Testing & CI | Unreal Engine 5 Gameplay Systems**

I am a Computer Engineering student focused on Python developer tools, testing and CI workflows, and Unreal Engine 5 gameplay systems. I investigate reproducible failures, make targeted improvements, and verify results with clear evidence and limitations.

**Core tools:** Python · pytest · Git / Git LFS · GitHub Actions · SQL / PostgreSQL · Celery · C++ · Unreal Engine 5 · Blueprints

[LinkedIn](https://www.linkedin.com/in/kaan-bartu-bozkurt-1b12b043b/) · [GitHub](https://github.com/kaanbartubozkurt)

## Selected engineering work

### Developer tools & backend

**[BranchRift — Git integration risk CLI](https://github.com/kaanbartubozkurt/branchrift)**
*Python · Git · Git LFS · CLI · CI*

A published Git CLI for assessing integration risks before branches come together. It checks divergence, same-path overlaps, binary-sensitive Unreal assets, Git LFS readiness, and ownership gaps. Its findings support human review rather than promising conflict-free merges.
[PyPI package](https://pypi.org/project/branchrift/) · [Source code](https://github.com/kaanbartubozkurt/branchrift)

**[Nativory — React Native / Android upgrade evidence](https://github.com/kaanbartubozkurt/Nativory)**
*Python · Gradle · React Native · Evidence verification*

An evidence-first tool for scoped React Native / Android upgrade checks. The `main` branch includes AGP/Gradle compatibility analysis and a unified `nativory scan` command with optional read-only Windows native-build log triage. Expo/FBJNI and ELF-alignment research remains experimental in [draft PR #2](https://github.com/kaanbartubozkurt/Nativory/pull/2). It does not certify Android builds or automatically repair projects.

**[Reprovant — Worker failure experiments](https://github.com/kaanbartubozkurt/reprovant)**
*Python · Celery · PostgreSQL · pytest*

A research workbench for reproducing worker failures, including duplicate side effects and state regressions. Controlled experiments and regression tests document observed behavior and its limits. **An engineering case study, not a commercially validated product or production certification.**
[Evidence case study](https://github.com/kaanbartubozkurt/reprovant/blob/main/docs/REPROVANT_EVIDENCE_CASE_STUDY.md)

### Gameplay engineering

**[False Normality — Psychological horror game](https://store.steampowered.com/app/4925070/)**
*Unreal Engine 5 · C++ · Blueprints · Gameplay systems*

Released on Steam on **September 15, 2026**. As part of a two-person team, I worked on gameplay logic, Blueprint systems, AI interactions, and player input behavior.

**[SON HAT — Supper's Ready / Civil Game Jam 2026](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/tree/integration/son-hat)**
*Unreal Engine 5.7 · C++ · Grappling · State-driven gameplay · Automation tests*

An **unfinished 48-hour game jam prototype** built around grappling traversal and timed rooftop rescue signaling. I primarily worked on C++ gameplay, rescue-state logic, HUD and interaction systems, testing, and integration. The source is available for technical review, but the **full playable city cannot be reproduced from this public repository alone**.
[Gameplay C++](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/blob/integration/son-hat/Source/UEIntroProject_1/GrappleComponent.cpp) · [Rescue-state logic](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/blob/integration/son-hat/Source/UEIntroProject_1/SonHatEvacuationDirector.cpp) · [Verification limits](https://github.com/kaanbartubozkurt/supper-ready-civil-game-jam-2026/blob/integration/son-hat/README.md)

## Selected open-source contributions

- **[booth — PR #31](https://github.com/Vedantgitbot/booth/pull/31) · Merged.** Handled malformed AI model output without crashing, with regression tests; the maintainer verified the fix and merged it.
- **[newsT — PR #26](https://github.com/StefanOOEOrg/newsT/pull/26) · Merged.** Rejected non-finite sentiment scores (`NaN` / infinities), including numeric strings, with targeted regression coverage.
- **[Cura AI — PR #121](https://github.com/slealq/cura-ai/pull/121) · PR submitted.** Corrected all-failed image-batch outcomes and made provider errors and partial failures more visible. Local verification: **1,069 backend tests passed** and TypeScript checks passed; no live end-to-end deployment verification claimed.

## What I can help with

- Reproducing and fixing focused **Python / pytest / GitHub Actions CI** failures.
- Investigating **state, retry and data-integrity** bugs, with regression coverage.
- Building and debugging **Unreal Engine 5 C++ / Blueprint gameplay systems**.

Available for focused freelance and contract work with clear deliverables and verification criteria.

**Contact:** [LinkedIn](https://www.linkedin.com/in/kaan-bartu-bozkurt-1b12b043b/)
