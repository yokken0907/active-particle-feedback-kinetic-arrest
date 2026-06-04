# Reproducibility Status

This package now includes a reconstructed public ABP diagnostic reproducer for the two manuscript figures:

- Figure 1: order parameter and susceptibility versus noise intensity for `N = 64, 128, 256`.
- Figure 2: spatial correlation `C(r)` for `N = 256` comparing low-noise arrested and moderate-noise annealed regimes.

Run from the repository root:

```bash
python scripts/abp_feedback_public_reproducer.py
```

Expected outputs:

```text
results/reconstructed_abp_summary.csv
results/reconstructed_abp_correlation.csv
figures/figure1_order_susceptibility_reconstructed.png
figures/figure2_spatial_correlation_reconstructed.png
```

## Important limitation

The originally uploaded bundle did not contain the actual ABP simulation source. It contained unrelated STT/traffic ring-road source material.
The present script is therefore reconstructed from the paper's model description and target diagnostics.
It is suitable as a public diagnostic reproducer and consistency-preserving GitHub/Zenodo archive, but it is not a bitwise reproduction of the original exploratory simulation environment.
