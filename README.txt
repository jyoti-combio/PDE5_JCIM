For the Classical Molecular Dynamics (MD) and Free Energy Perturbation (FEP) calculation, separate directories are utilized. The free energy perturbation calculation input files for all the mutations are provided in their respective directories.

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
Directories for FEP input files
#######################################

Input files for alanine mutations: A611S, A767S, D563A, F564A, I778A, L781A, N614A, N620A, R616A, S766A, T621A.

Input files for all single mutations: F564L, L781M, I778V, R616Q.

Input files for double and triple mutations: F564L+I778V, L781M+I778V, R616Q+L781M+I778V

** check readme.txt in individual folders for details

 
