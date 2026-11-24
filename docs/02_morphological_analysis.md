# 02 | Morphological analysis

**Method:** Break the design into functions; list feasible alternatives. Combining cells generates concepts, but combinations require compatibility and safety review.

| Function | A | B | C | D |
|---|---|---|---|---|
| Anatomical reconstruction | Mirrored anatomy | Local interpolation | NURBS surface reconstruction | Hybrid method |
| Material | Ti-6Al-4V ELI | Implant-grade PEEK | Reinforced PEEK (investigational) | — |
| Shell structure | Solid | Circular perforations | Hexagonal lattice | Graded lattice |
| Peripheral interface | Flush | Continuous overlapping lip | Discrete fixation tabs | Segmented overlapping lip |
| Fixation integration | Integrated holes | Separate mini-plates | Integrated tabs | Hybrid |
| Thickness | Uniform | Locally variable | Reinforced perimeter | Locally reinforced fixation |
| Load path intent | Curved shell | Radial reinforcement | Peripheral reinforcement | Graded stiffness |
| Edge profile | Rounded | Tapered | Stepped | Anatomically contoured |
| Manufacture | CNC machining | Metal powder-bed fusion | Validated high-temp polymer AM | Hybrid |
| Surface finishing | Smooth | Controlled texture | Region-dependent finish | — |

## Initial concept set
- **A:** Solid shell, continuous overlapping lip.
- **B:** Perforated shell, continuous overlapping lip.
- **C:** Hexagonal lattice shell, continuous overlapping lip.
- **D:** Graded lattice shell, continuous overlapping lip.
- **E:** Flush shell, discrete fixation tabs (optionally perforated).
- **F:** Radially reinforced shell, continuous overlapping lip.

## Compatibility / feasibility gates
1. Patient-specific anatomical compatibility.
2. Feasible manufacturing process for the candidate material and feature size.
3. Surgical exposure and fixation access.
4. Acceptable interface height, soft-tissue clearance and cleaning/finishing.
5. Traceable simulation and evidence-based verification.

Do not interpret these concepts as clinically feasible until they pass a formal review.
