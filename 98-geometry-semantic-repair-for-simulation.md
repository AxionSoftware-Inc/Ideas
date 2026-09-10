# Geometry Semantic Repair for Simulation

## Thesis
Imported CAD/BIM geometry is often visually correct but analytically broken. Repair it using semantic intent, not only geometric tolerances.

## Detect
- gaps and overlaps
- disconnected surfaces
- duplicated solids
- wrong normals
- impossible thin regions
- missing room boundaries
- doors/windows not cutting host geometry correctly
- accidental topology changes after import

## Key difference
A normal geometry healer asks whether surfaces close. A semantic healer asks whether the repaired object still means the same wall, slab, duct, room or structural member.

## Buyers
CAE preprocessors, BIM software, simulation consultancies.

## MVP
IFC room/building envelope -> watertight thermal/CFD domain with a repair report tied to IFC GUIDs.