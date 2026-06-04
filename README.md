# Active Particle Feedback Kinetic Arrest (APFKA)

**Current public release:** `v0.3.2-public-landing-and-metadata-refresh`  
**Project website:** https://yokken0907.github.io/active-particle-feedback-kinetic-arrest/  
**Repository:** https://github.com/yokken0907/active-particle-feedback-kinetic-arrest

APFKA is a claim-bounded repository archive for reduced active-particle feedback surrogate diagnostics. It studies kinetic-arrest-like behavior, noise-assisted annealing windows, feedback-geometry dependence, frustration-boundary classification, rescue-stability regimes, and persistent hard-boundary behavior in tested toy-model / reduced-surrogate settings.

This v0.3.2 release is a **public landing and metadata refresh** of the earlier v0.3.1 integrated revision. It reorganizes the repository for public readability, GitHub Pages use, search/discovery metadata, and stronger first-page claim-boundary communication. It does **not** introduce new physical, experimental, engineering, social, biological, or deployment claims beyond the archived v0.3.1 synthesis.

## Recommended paper

Start here:

- `paper/integrated_v0_3_1/APFKA_integrated_model_audit_synthesis_v0_3_1.pdf`

The integrated paper combines the earlier ABP-style model manuscript with the v0.2.0-v0.2.6 audit sequence. It preserves model equations and reconstructed diagnostics while narrowing the interpretation to model-internal diagnostics and failure-boundary behavior.

## Claim boundary

This repository may be described as:

> A reduced active-particle feedback surrogate diagnostic archive for kinetic-arrest-like behavior, noise-assisted annealing, feedback-geometry dependence, frustration-boundary classification, rescue-stability behavior, and persistent hard boundaries inside tested toy-model settings.

This repository does **not** claim:

- experimental validation in real active matter,
- material-design certification,
- device, colloid, robotics, or swarm-control deployment readiness,
- biological or social-system validation,
- civilization-level dynamics or crowd-control interpretation,
- public-policy applicability,
- a universal kinetic-arrest theorem,
- a formal proof of a phase transition,
- a complete hydrodynamic theory,
- or a production-ready simulation/control package.

The phrase "information feedback control" in this archive refers to a **mathematical feedback term inside a reduced active-particle toy model**. It must not be interpreted as a real-world behavioral-control method, crowd-control technology, public-policy method, material-design recipe, or safety-certified engineering controller.

## Technical visual orientation

A browser-friendly visual orientation is available at:

- `docs/index.html`
- `docs/project_visual_orientation/index.html`
- `docs/technical_visual_orientation/index.html`

For GitHub Pages, use:

```text
Settings -> Pages -> Build and deployment
Source: Deploy from a branch
Branch: main
Folder: /docs
```

Expected Pages URL:

```text
https://yokken0907.github.io/active-particle-feedback-kinetic-arrest/
```

## Repository structure

```text
paper/integrated_v0_3_1/       Recommended integrated manuscript
paper/addendum_v0_3_0/         Earlier synthesis addendum
figures/                       Figures and figure index
results/                       Reconstructed public ABP diagnostic outputs
results_summary/               Summary outputs
scripts/                       Public reproducer script
evidence/                      v0.3.0 synthesis/audit evidence
docs/                          Claim-boundary, release, and visual orientation materials
tools/                         Manifest verification utility
```

## Reproducibility note

This repository includes a reconstructed public ABP diagnostic reproducer. It is internally consistent with the paper-facing diagnostic figures and replaces previously mismatched source material, but it is not a bitwise recovery of the original exploratory simulation environment.

Run from the repository root:

```bash
python scripts/abp_feedback_public_reproducer.py
```

## License

License terms are source-defined in this repository:

- `LICENSE`
- `LICENSE_EVALUATION_ONLY.txt`

For Zenodo, use an `other-open` / source-defined / license-in-repository option rather than CC-BY-NC-4.0.

## AI assistance disclosure

AI assistance was used for drafting, code generation, numerical-audit scaffolding, repository organization, and manuscript preparation. The author remains responsible for final public claim boundaries, interpretation, and release decisions. See `AI_ASSISTANCE_DISCLOSURE.md`.
