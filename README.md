# OpenFF Lipid Validation \temp\

Pure and compositional bilayers.
  Lipid types with DOIs containing trajectories and topologies used for analysis:
  1. POPC [new fit zenodo link]
  2. POPE [new fit zenodo link]
  3. POPS [new fit zenodo link]
  4. PSM (SM16) [new fit zenodo link]
  5. POPC/15% Cholesterol [new fit zenodo link]
  6. POPC/50% Cholesterol [new fit zenodo link]

  - DOIs contain the production simulations.
	  - Trajectories were processed using trjconv -skip 10 for ease of upload and the first 100 ns have been removed.
    - 2.2.0 DOI: `10.5281/zenodo.14714284`

  - Lipid directories contain equilibration and production MD files in addition to topologies before and after refit.
  - Initial bilayer structures were built using OpenFF Interchange pdb structures in Packmol.
	- This workflow can be found here [].
  - Analysis scripts including APL, RDF, torsion and angle analysis, etc. can be found here [[OpenFF Bilayer](https://github.com/PEFrankel/OpenFF-Bilayer)].


## To-dos
* Add cutoff and water tests.
* Add control descriptions.
* Zenodo DOIs will contain additional info on OpenFF-specific mods (e.g. cutoff) since that is where it is relevant.
* Add mapping files + NMR ref
* Add a pic
