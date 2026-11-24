# 07 | Preliminary structural evaluation plan

**Not yet run.** This document describes proposed simulations only. These results would not establish clinical safety or motorcycle-impact protection.

## Comparative design matrix
Provisional three concepts (B, C, E) × candidate materials (Ti-6Al-4V ELI, implant-grade PEEK) × load cases. A solid overlapping shell can serve as a baseline.

## Candidate loads (magnitudes TBD from research)
- LC01: central localised load.
- LC02: off-centre localised load.
- LC03: distributed external pressure.
- LC04: near-boundary load for fixation assessment.

## Model fidelity progression
1. Verify units, solid integrity and material assignment.
2. Isolated implant with transparent simplified supports for a sanity check.
3. Bone segment plus implant with explicit contact assumptions.
4. Incorporate simplified fixation screws/connectors when the solver supports them.
5. Explore sensitivity to bone modulus, support conditions, load position and contact assumptions.
6. Run FEA mesh convergence checks and ensure the interpretation is robust.

## Requested outputs
| Output | Unit / meaning |
|---|---|
| Maximum inward displacement | mm; movement towards underlying tissues |
| Implant von Mises stress | MPa; candidate ductile material comparison, with qualification |
| Bone stress / strain | MPa or strain; bone anisotropy/heterogeneity limits |
| Implant–bone contact pressure | MPa; inspect regional distribution and edge peaks |
| Screw stress and reaction loads | MPa and N where modelled |
| Mass | g; volume × density |
| Elastic strain energy | J; under a consistent loading protocol |
| Mesh convergence | Change in key results with refinement |

## Caveats
- A force applied to an implant without realistic skull/support conditions cannot prove cranial protection.
- Stress concentrations at ideal sharp edges, point loads or fixed constraints may be numerical singularities.
- Clinical acceptance thresholds must come from evidence and specialist review, not guessed values.
- Real traumatic impact involves dynamics, contact and biological injury criteria beyond basic static FEA.
- Compare design variants under equivalent and clearly justified modelling conditions.
