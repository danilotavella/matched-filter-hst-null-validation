# Matched-Filter Stability Under Real Observational Noise

Reproducible notebook accompanying the Zenodo technical note:

**DOI:** https://doi.org/10.5281/zenodo.18762288

## Purpose

To test whether a matched-filter structural detection framework generates artificial statistical significance when applied to real observational data.

The validation is performed directly on HST ACS F814W skycell mosaics under realistic imaging conditions.

## Methodological components

- Sigma-clipping source masking  
- Gaussian smoothing (σ = 12 pixels)  
- Zero-mean halo template construction (σ = 10")  
- Local nuisance-plane regression  
- Empirical local-control distribution (60–120" annulus)

## Result

The matched-filter amplitude at the nominal center lies well within the empirical local-control distribution (p_low ≈ 0.40).

No spurious detection under real observational noise.

The notebook is fully reproducible.
