# Active Particle Feedback Kinetic Arrest v0.1.1-zenodo-safe-public-gate

This is the initial Zenodo-safe public-gate release package for the active-particle feedback kinetic-arrest manuscript archive.

## Scope

This release provides a paper companion archive for:

**Kinetic Arrest and Noise-Induced Annealing in Active Particle Systems with Information Feedback Control**

The manuscript studies an Active Brownian Particle (ABP)-type reduced numerical prototype with information feedback control that minimizes local variance of internal particle attributes.

The archive is intended for documentation, inspection, citation, independent review, and DOI archival through Zenodo.

## Central interpretation

The archive supports the limited claim that the tested reduced numerical model suggests kinetic-arrest-like fragmentation and noise-induced annealing behavior inside the modeled active-particle system.

It is not a universal theorem, not an experimental active-matter validation, and not an engineering deployment package.

## Included materials

- Manuscript PDF
- README and Japanese README
- Evaluation-only license
- Root LICENSE file
- File manifest with SHA-256 hashes
- Claim-boundary and limitation documents
- AI-assistance disclosure
- Result-summary JSON and CSV files
- Public-gate audit materials
- Source-material consistency audit
- Zenodo-safe draft citation metadata under `docs/citation_metadata/`

## Source-material consistency fix

A prior bundled source-material directory contained stochastic Optimal Velocity traffic/STT ring-road material rather than the ABP information-feedback simulation required for this manuscript.

That mismatched material has been excluded from the GitHub/Zenodo body.

This release is therefore positioned as a paper companion archive and public documentation package, not as a complete one-command reproduction-code package.

## Claim boundary

This release supports the limited claim that an ABP-type reduced numerical prototype with information feedback control exhibits model-internal kinetic-arrest-like behavior and noise-induced annealing in the tested configuration.

It does not claim:

- experimental active-matter validation;
- biological or social-system validation;
- civilization-scale dynamics;
- crowd-control or swarm-control technology;
- universal phase-transition proof;
- a rigorous theorem of kinetic arrest;
- complete hydrodynamic theory;
- complete reproduction code for every manuscript result.

## Zenodo-safe citation handling

The active root `CITATION.cff` file has been intentionally omitted from this pre-DOI release to avoid metadata-validation conflicts during Zenodo archival.

Draft citation metadata is preserved at:

`docs/citation_metadata/CITATION_DRAFT_pre_doi.cff`

After Zenodo DOI assignment, DOI metadata should be added to README, manuscript metadata, and citation files in a follow-up DOI-metadata release.

## Integrity check

The public package was checked before release.

- Manifest verification: PASS
- JSON parse: PASS
- Draft CFF YAML parse: PASS
- Root CITATION.cff: intentionally omitted
- Root LICENSE: present
- Git-ignore included-file conflict: 0
- Large files over 100 MB: none detected
- Compiled binaries: none detected
- Python syntax check: PASS
- AI assistance disclosure: present
- Claim-boundary documents: present
- Mismatched traffic/STT source material: excluded

## Suggested tag

`v0.1.1-zenodo-safe-public-gate`

## Reproducibility upgrade in complete checkfix package

This complete checkfix package adds a reconstructed public ABP diagnostic reproducer:

- `scripts/abp_feedback_public_reproducer.py`
- `results/reconstructed_abp_summary.csv`
- `results/reconstructed_abp_correlation.csv`
- `figures/figure1_order_susceptibility_reconstructed.png`
- `figures/figure2_spatial_correlation_reconstructed.png`

The previously mismatched STT/traffic source material remains excluded.
The new reproducer is reconstructed from the manuscript-level model description and target diagnostics, and is not claimed to be a bitwise copy of the original exploratory ABP code.
