# Lipidomics study with Magainin II

Antimicrobial peptides (AMPs) play a vital role in the innate immune system of all living organisms.[1,2] These peptides can identify and disrupt lipid patterns in bacterial membranes without harming healthy cells.[3] Notably, AMPs often possess shared properties: they typically consist of 10–40 residues, adopt an α-helix secondary structure when they interact with membranes, maintain a positive net charge, and contain a significant number of non-polar residues. These features, along with their pronounced transversal hydrophobic moment in their folded state, facilitate interactions with lipid bilayers. Thus, the use of these molecules as therapeutic agents is an obvious lesson from Nature that can be exploited to design new antibiotics, anticancer or antiaging drugs.[4]

In this tutorial, we will investigate the potential antimicrobial properties of Magainin-II (Mag2), one of the most well-known natural AMPs.[5] We will simulate it in the presence of two different membrane models: one representing a healthy membrane (POPC), and the other a bacterial bilayer (POPC-POPG 3:1). We’ll place several AMPs in the aqueous phase of our systems and run simulations, analysing potential spontaneous peptide-bilayer interactions. 

Throughout this tutorial, you will learn how to perform a Molecular Dynamics (MD) simulation using coarse-grained (CG) resolution with the Martini Force Field. To begin, follow the steps in the provided Google Colab notebook. The necessary data for the tutorial is available at: [https://zenodo.org/records/13838553](https://zenodo.org/records/13838553).

Run the **Tutorial2_Lipidomics-Mag2.ipynb** file with Google Colab and enjoy! 

PD: If you prefer to run the tutorial on your own machine, you can download the notebook through this [link](../jupyter-notebooks/Tutorial2_Lipidomics-Mag2_Jupyter.ipynb). It is necessary to have GROMACS and a series of Python libraries (vermouth, MDAnalysis and nglview) installed. The notebook includes tips on how to install them.

1 – Lancet Infect Dis. 9, e216; doi: 10.1016/S1473-3099(20)30327-3 (2020)

2 – Front. Microbiol. 11; doi: 10.3389/fmicb.2020.582779 (2020)

3 – Colloids Surf. B Biointerfaces 196, 111349; doi: 10.1016/j.colsurfb.2020.111349 (2020)

4 – Front. Immunol. 15, doi: 10.3389/fimmu.2024.1320779 (2024)

5 – BBA. 1327, 119; doi: 10.1016/S0005-2736(97)00051-5 (1997)
