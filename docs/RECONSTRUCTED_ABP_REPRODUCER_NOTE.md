# Reconstructed ABP reproducer note

The originally uploaded repository bundle did not contain the Active Brownian Particle information-feedback simulation source corresponding to the manuscript.
It contained a stochastic Optimal Velocity traffic/STT ring-road source directory instead.

This release therefore adds a reconstructed public ABP diagnostic reproducer:

- `scripts/abp_feedback_public_reproducer.py`
- `results/reconstructed_abp_summary.csv`
- `results/reconstructed_abp_correlation.csv`
- `figures/figure1_order_susceptibility_reconstructed.png`
- `figures/figure2_spatial_correlation_reconstructed.png`

The script is reconstructed from the manuscript-level model description and reported diagnostics:

1. finite-size order-parameter and susceptibility behavior for `N = 64, 128, 256`;
2. stronger long-range spatial correlation at moderate noise than in the low-noise arrested regime for `N = 256`.

## Claim boundary

This reconstructed script is a public manuscript-level diagnostic reproducer, not a bitwise recovery of the author's original exploratory simulation code.
It supports a stronger public reproducibility posture than the previous paper-companion-only package, but it should still be cited as a reconstructed public reproducer unless the original local ABP code is later recovered and added.
