# Mastery Track: Kinesiology & Human Movement

[![License: MIT](https://img.shields.io/badge/license-MIT-1B4332?style=flat-square&labelColor=0d1117)](./LICENSE) [![Mastery Track](https://img.shields.io/badge/Mastery%20Track-The%20Human%20System-2F5233?style=flat-square&labelColor=0d1117)](https://github.com/RoyPiring) [![Progress](https://img.shields.io/badge/progress-0%2F100-7B42BC?style=flat-square&labelColor=0d1117)](#committed-projects) [![Updated](https://img.shields.io/badge/updated-2026--07--13-264653?style=flat-square&labelColor=0d1117)](#version)

> *A hands-on route from amateur to command in kinesiology and human movement, built one end-to-end project at a time. A route to command, not a degree.*

| | |
|--|--|
| Tier | Mastery (Mastery learning-path group) |
| PoV contract | PoV-CI: the journey of an amateur becoming a master by doing, adapted to Kinesiology |
| Catalog (the menu) | `ideas/mastery-kinesiology-100/` (100 ranked hands-on systems) |
| Standard | `governance/MASTERY_STANDARD.md` (binding baseline) |
| Target systems | 100 (the catalog menu; onboard do-first, starting rank 1) |
| Status | 0 / 100 onboarded |
| GitHub remote (per build) | a private repo per build, created by the build (rule 27) |

## What lands here

The mastery repo for Kinesiology. It holds the hands-on end-to-end LEARNING systems from the catalog `ideas/mastery-kinesiology-100/`, onboarded one at a time as generator-ready project builds. Each project is a real thing you build, run, and check against a known result, and together they take an amateur to principal-level command of Kinesiology, the point where you could run your own business or be the go-to expert. The operator's edge here is biomechanics modeling (OpenSim and OpenCap), wearable and movement analytics, and machine learning on movement.

## The honest route (read first)

Two-route honesty: to practice, a relevant degree plus professional certifications (no PhD needed); to research, a funded PhD. This is a hands-on route to subject-matter command, not a certification or a license.

## PoV reminder (PoV-CI, Kinesiology)

The point of view is a self-directed learner-kinesiologist and sports-technology founder on the road to subject-matter command, in deliberate-practice mode. Research is always in service of the build, never academics for its own sake. Every project produces a runnable artifact with a concrete self-check, and the late-wave projects are the principal's own work (running the practice, shipping the product, and defending the mastery). The path is a launchpad for continued growth, not a terminus.

## Build constraints

AI-native and agent-based. Each project is built by an orchestrated swarm of 10 to 50 AI agents running in parallel with loops and goals, into up to ten full end-to-end systems, on the approved flat-rate clients plus free and open-source tooling over public data. Operator build-time budget: 90 minutes (a minimum prototype pass that then deepens over deep-work sessions for the heavy builds). The agents do the heavy lifting so the operator focuses on mastery.

## Signature artifact (mastery proof)

Every project here ships the validated learning system, exercise, or model, plus its concrete self-check result (the output matched against the known reference, benchmark, code requirement, or reproduced study named in the catalog row), plus a teach-back proving the operator can do it again and can teach it to a novice. That is how the project proves mastery of that piece of the craft, not just that it was read about.

## Safety and honesty layer (binding)

Higher real-body-testing bar: PAR-Q+ health screening, qualified supervision, and clinician oversight for at-risk or clinical populations. A certification is a credential, not a license; the clinical and testing entries are guideline-translation study builds, not prescriptions for real people.

## Onboarding process (the same pipeline as the other repos, PoV-CI)

To onboard a catalog system as a project build:

1. Pick a system from `ideas/mastery-kinesiology-100/` in do-first order (start at rank 1; see the catalog's RANKING waves). Run intake triage (`pipeline/07_pipeline_intake_triage.md`).
2. Ingest it into a single markdown project file at `projects/NN_<system-shorthand>.md`, following `templates/PROJECT_SCAFFOLD.md` at pipeline_version 0.17.0, PoV-CI. The kickoff scenario is the learner's own decision to build this system to gain mastery (the "client" is the operator's mastery goal and the field's standard), in the learner-persona's voice. The build is the catalog row's hands-on end-to-end build, and the catalog row's concrete self-check is the project's validation. Carry the single-build directive (rule 25), the R4 self-check (rule 26), the design-first pre-artifacts and the post-artifacts (rule 24), and the delivery rails (rule 27: the build creates a private GitHub repo and a Linear project, worked branch-by-branch through pull requests, ending in a tagged release and plain-language repo docs).
3. Validate mechanically: `python scripts/verify_project.py projects/NN_<system-shorthand>.md --paste` must return GO before pasting into the V2 generator.
4. Run the four audits: quality gate (99+), Codex cross-eval (findings-clean), currency, and simple-language, plus the safety layer above. Nothing ships with an open high-confidence finding.
5. Commit the single file to `projects/`, update the repo Status line and `governance/MASTERY_LEDGER.md`, and write a run log.

## Candidate first projects (do-first, from the catalog)

- **1. The Kinesiology Concept Map** (catalog rank 1)
- **2. Science or Practice: The Decision** (catalog rank 2)
- **3. Functional Anatomy** (catalog rank 3)
- **4. The Sub-Disciplines Reproduction Sprint** (catalog rank 4)
- **5. The Math and Code On-Ramp** (catalog rank 5)

Onboard these first; the full 100-system menu queues behind them in the catalog's RANKING do-first order.

## Project folder layout

```
projects/
  01_<system-shorthand>.md      one standalone generator-ready file per project (rule 16)
  02_<system-shorthand>.md
  ...
```

## Standing rules

1. One file per project, standalone both ways (rule 16).
2. PoV-CI is binding on every S0, R1, R2, R3, and R4; the amateur-to-master, principal-level, hands-on-not-academic framing holds (the Mastery Standard).
3. The catalog row's concrete self-check is the project's validation, a runnable artifact matched to a known result, never a vague "checked against the literature".
4. The safety and honesty layer above is binding on every payload.
5. Quality gate 99 minimum; `verify_project.py --paste` returns GO before any paste.

## Version

v0.1.0: 2026-07-12. Established as the mastery repo for Kinesiology, the third of the six Mastery group repos, structured on the same onboarding process as the ten portfolio repos and governed by the Mastery Standard.
