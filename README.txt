For the Classical Molecular Dynamics (MD) and Free Energy Perturbation (FEP) calculation, separate directories are utilized. The "FEP_Input" directory correspond to the free energy perturbation calculation input files for all the mutations. We have provided files for Alanine mutations, Single mutations and Double_Triple mutations in three separate directories.

############################################
Classical MD directory - Classical_MD_Input
############################################
This directory has following files:

Complex_ionized.pdb; reference coordinates for the PDE5_EVO complex

Complex_ionized.psf; contains partial charges of each atom for the PDE5_EVO complex

equil.coor; coordinates from the previously equilibrated step

equil.xsc; extendedSystem configuration file from the previously equilibrated step

TIPS3P_water_ions.prm; water parameters

par_all36_prot.prm; protein parameters

ligand_EVO.prm; ligand parameters

par_all36_cgenff.prm; ligand parameters



setup.namd; NAMD ADJUSTABLE PARAMETERS

** use setup.namd file to run the classical MD simulation of the PDE5_EVO complex


#######################################
FEP directory - FEP_Input
#######################################
This directory has following folders:

Alanine_Mutations; Input files for all alanine mutations

Single_Mutations; Input files for all single mutations

Double_Triple_Mutations; Input files for double and triple mutations

** check readme.txt in individual folders for details

 
