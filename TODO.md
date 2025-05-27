# TODO

## Globals

- Standardize on OSPRAE vs. "LSST Science Pipelines" throughout.  Pending on Leanne looking into processes for getting feedback on major renaming.
- Standardize on LSST vs. Rubin where neither is obviously more appropriate than the other.
- Standardize on how to format section references.
- Standardize or remove references to dataset types.
- Do we link to Python documentation for code or not (some in at least the `CalibrateImageTask` section).

## Citations/links needed

- HTCondor and PanDA (Pipelines and Tasks)
- SDSS Photo and Pan-STARRS IPP (Core)
- Eigen, GSL, Boost, StarLink AST (Core)
- Astropy (Core).

## Possibly-unnecessary detail

For the particularly big pieces that don't have good external docs to link to, maybe we make some appendices, so we can include the text without unbalancing the paper structure?

- pex_config (Middleware)
- Pipeline Visualization (Middleware)
- Amp Offset Correction (ISR)

## Section editing/writing

### ISR

- Effectively has two introductions about what ISR is.
- Doesn't need an `ip_isr` heading; should just mention that the ISR code lives in the `ip_isr` package
- Needs to mention both `IsrTask` and `IsrTaskLSST` and say what they're both for, even if we focus our attention on the latter.
- Amp-offset correction is half of the text (maybe move to appendix?)

### Object Production

- Needs to be written.

### DIA filtering

- Too much detail on streak-finding
- Satellite risk to Rubin is sort of out of scope for a software paper.
- Should cover reliability scoring as well (probably mostly).

### drp_pipe

- Needs to be written (doesn't need much; note how short cp_pipe and ap_pipe sections are).

### analysis_tools

- Needs a bit more about how it works - builds on PipelineTask + Config, has common plot types, aggregates multiple analyses into metrics bundles, etc.
- Maybe say something about advantages/differences from faro, since that's also had published descriptions?

### conclusion

- Needs to be written (just a stub at present).

