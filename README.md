# SOD2-SIRT2-Fisetin
Fisetin disrupts mitochondrial homeostasis via the SIRT2-SOD2-mtROS pathway in pancreatic adenocarcinoma

#SOD2
To obtain a reliable tetramer structure of SOD2, the SWISS-MODEL and MD simulation were utilized based on the 1AP5 model from PDBj. 

#SOD2+Fisetin
AutoDockTools 1.5.7 was used to keep polar hydrogens, calculate Gasteiger charges, and generate the PDBQT format of SOD2 for global docking. Molecular docking of SOD2 and fisetin was carried out by semi-flexible molecular docking using Autodock 4.2.6. In addition, the box for SOD2 and fisetin was 90 × 90 × 90 Å at a resolution of 0.375 Å. The parameter file specified 1000 Lamarckian genetic algorithm runs.

#SIRT2+Fisetin
The 3D structure of SIRT2 was obtained from the RCSB (PDB ID: 4RMI). PDBQT format for ligand-based docking was generated using AutoDockTools 1.5.7. Semi-flexible molecular docking with Autodock Vina 1.2.3 was used for the docking of SIRT2 and fisetin. In addition, the box for SIRT2 and fisetin was 15.3 × 21.4 × 17.8 Å and the center coordinates of the grid box were -16.6, 4.1, 9.2 (x, y, z).
