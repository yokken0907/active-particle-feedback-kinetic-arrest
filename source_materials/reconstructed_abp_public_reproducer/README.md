# Reconstructed ABP public reproducer

This directory preserves the public reconstructed ABP diagnostic reproducer used in this archive.
The original uploaded package contained an unrelated STT/traffic simulation under `source_materials`.
That mismatched material was excluded. This replacement script was reconstructed from the manuscript's ABP model description and target diagnostics.

Run from the repository root:

```bash
python scripts/abp_feedback_public_reproducer.py
```

It regenerates the archived CSV files and figures for the manuscript-level diagnostics.
