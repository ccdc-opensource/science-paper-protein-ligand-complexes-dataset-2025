# science-paper-protein-ligand-complexes-dataset-2025

## Dataset

This is a dataset of protein-ligand complex structures collected for assessment of cavity determination algorithms.

It contains 486 complex structures.

### Dataset structure

The dataset folder contains 486 subfolders named `PDBID_CCDID`. Each folder contains 5 files:

- `PDBID_prepared_protein.pdb`
- `PDBID_prepared_protein.cif`
- `PDBID_prepared_protein_cofactors.pdb`
- `PDBID_prepared_protein_cofactors.cif`
- `CCDID_prepared_ligand.mol2`

`PDBID_prepared_protein.pdb` and `PDBID_prepared_protein.cif` contain a porocessed structure of the protein only, `PDBID_prepared_protein_cofactors.pdb` and
`PDBID_prepared_protein_cofactors.cif` include, in addtition to the protein structure, protonated cofactors and metal atoms located near the protein's binding pocket.
`CCDID_prepared_ligand.mol2` contains a structure of a protonated ligands.
