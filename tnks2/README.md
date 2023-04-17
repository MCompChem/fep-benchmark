# FEP+ input and results for TNKS2 dataset

This folder contains:
- protein structure prepared with Maestro Protein Preparation Wizard.
- ligands.sdf: 3D conformations of the ligands in the binding site. Prepared with LigPrep.
- results_5ns.csv: FEP+ results with sampling time of 5ns.
- results_20ns.csv: FEP+ results with sampling time of 20ns.
- results_edges_5ns.csv: FEP+ results for individual edges with sampling time of 5ns.
- results_edges_20ns.csv: FEP+ results for individual edges with sampling time of 20ns.
- results_neutral_X: equivalent files but for subset of 21 compounds that are neutrally charged. This is a submap of the total map that was run. These results are shown to illustrate that the error in the set of 27 compounds is dominated by the errors in those transformation that involve charge changes (the initial FEP map was essentially split into two clusters).
- results_glide_dock.csv: Glide docking scores for free docking of ligands
- results_glide_score_inplace.csv: Glide docking scores of FEP+ input poses (refine option)
- results_prime.csv: Prime MM-GBSA scores of FEP+ input poses
