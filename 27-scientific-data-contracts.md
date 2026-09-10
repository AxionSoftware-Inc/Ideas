# Scientific Data Contracts

## Idea
Define strict machine-readable contracts for scientific datasets so bad data is rejected before it silently contaminates a model or simulation.

A data contract declares:
- variable meaning
- units and dimensions
- coordinate frame / orientation
- sign convention
- uncertainty / measurement error
- sampling rate / timestamps
- missing-data policy
- valid ranges
- calibration state
- sensor/model provenance
- schema/version compatibility

## Example
```text
velocity:
  type: vector3
  units: m/s
  frame: body_fixed
  valid_range: [-120, 120]
  uncertainty: 0.04 m/s
```

If another dataset supplies velocity in `km/h`, world coordinates, or without calibration metadata, the system converts safely or refuses the merge.

## Material value
A large fraction of engineering failures are integration errors rather than difficult mathematics. Data contracts reduce debugging time and bad downstream decisions in digital twins, simulation pipelines and scientific ML.

## Strategic value
This is the type system for scientific data. It complements Semantic Scientific Objects, Model ABI, Provenance Graph and Scientific CI.

## Differentiation
Generic schemas validate shape and field names. Scientific contracts validate physical meaning.

## MVP
JSON/YAML schema + runtime validator for units, dimensions, ranges, coordinate frames and uncertainty metadata. Integrate with pandas/Arrow/Parquet first.