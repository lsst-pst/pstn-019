# TODO

## Globals

- Standardize on OSPRAE vs. "LSST Science Pipelines" throughout.  Pending on Leanne looking into processes for getting feedback on major renaming.
- Standardize on LSST vs. Rubin where neither is obviously more appropriate than the other.
- Standardize on how to format section references.
- Standardize or remove references to dataset types.

## Citations/links needed

- HTCondor and PanDA (Pipelines and Tasks)
- SDSS Photo and Pan-STARRS IPP (Core)
- Eigen, GSL, Boost, StarLink AST (Core)
- Astropy (Core).

## Possibly-unnecessary detail

For the particularly big pieces that don't have good external docs to link to, maybe we make some appendices, so we can include the text without unbalancing the paper structure?

- Periodic logging and deferred string formatting in logging (Fundamentals)
- Enumeration pytest advantages; we can leave that to pytest docs (Unit Testing and Code Coverage).
- pex_config (Middleware)
- Pipeline Visualization (Middleware)
- Amp Offset Correction (ISR)

## Section editing

### ISR

- Effectively has two introductions about what ISR is.
- Doesn't need an `ip_isr` heading; should just mention that the ISR code lives in the `ip_isr` package
- Needs to mention both `IsrTask` and `IsrTaskLSST` and say what they're both for, even if we focus our attention on the latter.
- Amp-offset correction is half of the text (maybe move to appendix?)

