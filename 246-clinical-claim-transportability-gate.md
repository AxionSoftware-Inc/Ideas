# Clinical Claim Transportability Gate

## Idea
Determine whether a biomedical model or digital-twin claim validated in one cohort/site/device context can be trusted in another.

## Pipeline
`source evidence + target population/site + model assumptions -> distribution shift -> causal/measurement differences -> uncertainty -> GO / SHADOW / REVALIDATE / NO-GO`

## Outputs
- transportability score
- missing validation strata
- site/device measurement shifts
- unsupported extrapolations
- minimum additional evidence needed

## Buyers
Hospitals, digital-health vendors, diagnostics, pharma and regulators.

## Moat
Explicit claim-to-context reasoning tied to validation evidence and measurement semantics.