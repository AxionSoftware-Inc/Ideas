# Image-to-Measurement Uncertainty Compiler

Propagate uncertainty from optics, calibration, sampling, segmentation and image processing into the final scientific quantity.

Example:
`raw fluorescence -> background correction -> segmentation -> intensity integration -> concentration estimate`

The compiler reports which stage dominates uncertainty and whether the final claim is resolution/calibration limited.

**MVP:** object size/count/intensity measurements with explicit uncertainty budgets.
