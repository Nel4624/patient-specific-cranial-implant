# Patient-Specific Cranial Implant | Engineering Design Study

**Status:** Concept development and anatomical preprocessing  
**Start:** 24 November 2026  
**Primary objective:** Evaluate patient-specific cranial implant concepts for mechanical protection, anatomical restoration, stable fixation and patient-centred outcomes.

> Educational internship design challenge. No implant design here is clinically approved, validated for implantation, or suitable for patient use.

## Design methodology
1. Clarify clinical problem, stakeholders, constraints and available anatomy.
2. Research cranioplasty, skull anatomy, fixation systems, biomaterials and regulatory considerations.
3. Define measurable requirements and evidence sources.
4. Perform morphological analysis and generate concepts.
5. Conduct qualitative pros/cons assessment; apply hard safety/feasibility gates and a weighted decision matrix.
6. Select **three concepts** for detailed CAD and controlled comparative FEA.
7. Validate geometry, test modelling assumptions and perform FEA convergence checks.
8. Compare results, select and refine a concept, and produce a non-clinical physical prototype.
9. Compile a traceable engineering report and presentation.

## Current concept directions
- Overlapping peripheral lip with a solid or perforated shell.
- Overlapping lip with an optimised lattice shell.
- Flush-fit shell with discrete fixation tabs as an alternative interface.

**No concept or material has yet been validated or formally selected.** Titanium alloy and medical-grade PEEK are candidates pending evidence review.

## Project documentation
- [Project brief and requirements](docs/01_design_requirements.md)
- [Morphological analysis](docs/02_morphological_analysis.md)
- [Concept trade-offs](docs/03_concept_tradeoffs.md)
- [Concept selection methodology](docs/04_concept_selection.md)
- [Materials and manufacturing](docs/05_materials_manufacturing.md)
- [CAD and geometry processing](docs/06_CAD_workflow.md)
- [FEA plan](docs/07_FEA_plan.md)
- [Research log](docs/08_research_log.md)
- [Design decision log](docs/09_decision_log.md)
- [Reporting structure](report/README.md)
- [Local data handling](DATA_HANDLING.md)

## Cross-computer workflow
- **MacBook:** Blender, skull geometry inspection, mesh simplification, reconstruction and quality checks.
- **Lenovo:** SolidWorks, parametric/surface modelling, implant design and available FEA.
- **GitHub:** Text documentation, scripts, task tracking and non-confidential results.
- **Approved local transfer:** Original patient-specific STL, derived anatomy, CAD, FEA binary files and prototype exports.

Do not add patient-specific files to this repository or cloud sync without explicit permission from the challenge provider.

## Milestones
1. Inspect original anatomy and confirm model units, topology and defect location.
2. Construct a simplified representation while quantifying geometric deviation.
3. Confirm a credible SolidWorks-compatible CAD/FEA workflow.
4. Reconstruct target contour and prototype the interface.
5. Compare shortlisted designs through supported simulations and document limitations.
