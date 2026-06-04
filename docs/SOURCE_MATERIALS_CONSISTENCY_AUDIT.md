# Source-material consistency audit

## Finding

The uploaded paper discusses an Active Brownian Particle model with information feedback control, local variance minimization, finite-size order parameters, susceptibility, and spatial correlation diagnostics.

The source-material directory originally bundled with the project contained stochastic Optimal Velocity traffic/STT ring-road simulation material, not the ABP information-feedback simulation required for this manuscript.

## Action taken

The mismatched STT/traffic source material was excluded from the public GitHub/Zenodo body.
A reconstructed ABP public diagnostic reproducer was added under:

```text
scripts/abp_feedback_public_reproducer.py
source_materials/reconstructed_abp_public_reproducer/
```

## Result

The repository is now internally consistent as an ABP paper companion archive with reconstructed manuscript-level diagnostic reproduction.
It should not be described as containing the original ABP simulation code unless that code is later recovered and added.
