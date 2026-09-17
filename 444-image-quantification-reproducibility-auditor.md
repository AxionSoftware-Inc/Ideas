# Image Quantification Reproducibility Auditor

Audit whether an image-analysis pipeline can reproduce the claimed quantitative result across users, software versions and reasonable parameter choices.

Checks:
- preprocessing dependence
- threshold/segmentation sensitivity
- normalization choices
- analyst variability
- hidden manual edits
- software/model version drift
- robustness of downstream statistics

Output: reproducibility passport and fragile-analysis warnings.
