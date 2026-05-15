# Active Particle Feedback Kinetic Arrest

This repository accompanies the AI-assisted independent research manuscript:

**Kinetic Arrest and Noise-Induced Annealing in Active Particle Systems with Information Feedback Control**

Author: Keiji Yoshimura, Independent Researcher  
Status: GitHub-ready paper companion archive v0.1.1-public-gate

## Simple Japanese classification title

**能動粒子系・情報フィードバック制御の非平衡相転移理論**

## Scope

This project studies Active Brownian Particle (ABP) systems with an information feedback control term that reduces local variance of internal particle attributes. Numerical simulations explore finite-size dependence, orientational order, susceptibility peaks, spatial correlations, kinetic arrest, and noise-induced annealing.

The repository is a paper companion archive for a reduced non-equilibrium statistical-physics simulation study.

## Central interpretation

The work should be read as a theoretical and numerical prototype showing that, in an active-particle system with feedback-mediated local variance minimization, very low noise may trap the system in fragmented metastable domains, while moderate noise can help restore longer-range correlations.

## Technical Visual Orientation

For technically interested first-time readers, this repository includes a browser-only technical visual orientation page:

`docs/technical_visual_orientation/index.html`

This page provides an active-particle-specific overview of the feedback kinetic-arrest / noise-induced-annealing logic. In this repository, the mission variable is not material design certification, experimental active-matter validation, or device deployment; it is modeled kinetic-arrest / noise-induced-annealing diagnosis, meaning that a reduced active-particle system is used to distinguish persistent arrest, feedback-assisted escape, noise-assisted annealing, order-parameter recovery, and artifact-like control effects under a strict simulation/provenance boundary.

The page also summarizes active-particle simulation state channels, mobility/order diagnostics, feedback and noise channels, artifact-audit discipline, reconstructed-public-reproducer provenance caution, evidence hierarchy, repository reading order, and the claim boundary. All major visual sections include replay controls so that readers can step through the diagnostic logic rather than viewing a static template.

The page is intended only as an orientation aid. It does not run active-particle simulations, does not validate an experimental material system, does not certify material design, device deployment, industrial process readiness, or safety, and does not replace the manuscript, source materials, figures, or independent expert review.

## What this repository does not claim

This repository does **not** claim:

- experimental validation in real active matter,
- biological or social-system validation,
- civilization-level control theory,
- practical crowd-control or swarm-control technology,
- guaranteed phase-transition universality,
- formal proof of kinetic arrest,
- or a production-ready simulation package.

## Repository status

This is a compact paper companion archive. It is not a complete virtual environment, not an experimental active-matter dataset, and not an engineering-control implementation.

## PUBLIC-GATE-0 status

Decision: `PASS-WITH-MINOR-PUBLICATION-FIXES-A10-ACTIVE-PARTICLE-PUBLIC-GATE-0`  
Public version: `v0.1.1-public-gate`  
Classification: 能動粒子系・情報フィードバック制御の非平衡相転移理論

This repository is a public-gate copy reviewed under an A10 Evidence-Lock Protocol style gate. The gate fixes the claim boundary, non-claims, manifest policy, and GitHub/Zenodo/Jxiv publication posture.


## Zenodo-safe metadata handling

The active root `CITATION.cff` file is intentionally omitted in this pre-DOI release to avoid metadata-validation conflicts during Zenodo archival.

Draft citation metadata is preserved at:

`docs/citation_metadata/CITATION_DRAFT_pre_doi.cff`

## Source-material consistency note

During the checkfix audit, a previously bundled source-material directory was found to contain stochastic Optimal Velocity traffic/STT ring-road material rather than an ABP information-feedback simulation for this manuscript. That mismatched material has been excluded from the public GitHub/Zenodo body.

This release now includes a reconstructed public ABP diagnostic reproducer for the manuscript-level Figure 1 and Figure 2 diagnostics. The reproducer is not a bitwise recovery of the original exploratory code, but it replaces the previously mismatched STT/traffic source material with an internally consistent ABP-oriented public reproduction path.

Run from the repository root:

```bash
python scripts/abp_feedback_public_reproducer.py
```
