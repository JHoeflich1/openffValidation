# OpenFF Lipid Validation \temp\

Pure and compositional bilayers.
  Lipid types with DOIs containing trajectories and topologies used for analysis:
  1. POPC [2.2.0 zenodo link] [new fit zenodo link]
  2. POPE [2.2.0 zenodo link] [new fit zenodo link]
  3. POPS [2.2.0 zenodo link] [new fit zenodo link]
  4. POPC/15% Cholesterol [2.2.0 zenodo link] [new fit zenodo link]
  5. POPC/50% Cholesterol [2.2.0 zenodo link] [new fit zenodo link]
  6. PSM (SM16) [2.2.0 zenodo link] [new fit zenodo link]

  - DOIs contain the 500 ns MD production simulations.
	- These were processed using trjconv -skip 10 for ease of upload. Original analysis was performed on the full trajectories.

  - Lipid directories contain equilibration and production MD files in addition to topologies before and after refit.
  - Initial bilayer structures were built using OpenFF Interchange pdb structures in Packmol.
	- This workflow can be found here [].
  - Analysis scripts including APL, RDF, torsion and angle analysis, etc. can be found here [].


* Add cutoff and water tests.
* Add control descriptions.
* Zenodo DOIs will contain additional info on OpenFF-specific mods (e.g. cutoff) since that is where it is relevant.
* Add mapping files + NMR ref
