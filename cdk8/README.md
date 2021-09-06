# FEP+ input and results for CDK8 dataset

This folder contains:
- protein structure prepared with Maestro Protein Preparation Wizard. Only chain A = CDK8 was used. The X-ray is a complex with a Cyclin.
- ligands.sdf: 3D conformations of the ligands in the binding site. Prepared with LigPrep.
- results_5ns.csv: FEP+ results with sampling time of 5ns.
- results_20ns.csv: FEP+ results with sampling time of 20ns.
- results_edges_5ns.csv: FEP+ results for individual edges with sampling time of 5ns.
- results_edges_20ns.csv: FEP+ results for individual edges with sampling time of 20ns.

For this test case, the top of the assay appears to be around 10 nM as reliable Kd.

The actual assay used for CDK8 is described in footnote 29, which does not give the test concentrations of ligand used but does note the concentrations of CDK8 (5 nM) and the competitive ligand (10 nM):

FRET based Lanthascreen binding competition assay: A dye-labeled ATP competitive probe served as a FRET acceptor upon binding to CDK8 labeled with a strepavidin-Eu-chelate (via a biotinylated anti His antibody). The result was a fluorescence signal at 647 nm. When this ATP competitive probe is displaced by an inhibitor, the signal is repressed. CDK8 used for this assay was co-expressed with Cyclin C (Invitrogen #PV4402, 80% purity). The assay procedure for an assay in 1536 well plate format was performed as follows: 2 μL CDK8/biotin-anti-His Ab/SA-Eu mix in assay buffer (pH 7.5) were pipetted into the wells of a micro plate. 1 μL compound in 20 mM Hepes buffer/5% DMSO was added. The plate was shaken for 30 s and incubated for 20 min at rt. 2 μL Alexa647-probe in assay buffer were added. The plate was shaken for 30 s again and incubated for 60 min at rt in the dark. Then the plate was read on a Perkin Elmer Envision (mode LANCE/TRF, excitation 340 nm emission 650 nm). The assay buffer was 50 mM Hepes pH 7.5 (Merck # 1.10110), 10 mM MgCl2 (Merck #1.05833), 1 mM EGTA (Merck #1.08435), 0.01% Brij-35 (Pierce #28316). The final concentrations of the reaction components in 5 μL total assay volume were: 1% DMSO (Merck # 1.02950), 5 nM CDK8/Cyclin C (Invitrogen #PV4402), 2 nM biotin-a-His Ab (Invitrogen #PV6089), 2 nM SA-Europium (Invitrogen #PV5899), 10 nM Alexa647-Tracer (Invitrogen #PV5592).

As noted here, the limiting component (in this case, CDK8) should be several-fold lower than the measured Kd to give a reliable measure of Kd. As such, any Kds <= about 10 nM should be considered suspect and unreliable, as 10 nM represents the reliable floor for this assay.
