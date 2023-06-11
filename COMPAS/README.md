# COMPAS

The repository of The COMPAS Project: a COMputational database of Polycyclic Aromatic Systems

## Content

### COMPAS-1x
This dataset contains ∼34k cata-condensed polybenzenoid hydrocarbons calculated at the GFN2-xTB level. The dataset contains the following data:

|  Data column header | Description |
|-------------|-------------|
| molecule | Identifier of the molecule (includes the molecular formula and a serial number) |
| smiles | SMILES string of the molecule |
| balaban_notation | annulation sequence after Balaban et al. notation |
| augmented_lalas | annulation sequence with angular directionality (aka augmented LALA string) |
| lalas | annulation sequence without angular directionality (aka LALA string) |
| HOMO_eV | HOMO energy in eV |
| LUMO_eV | LUMO energy in eV |
| GAP_eV | HOMO-LUMO gap in eV |
| Dipmom_Debye | Dipole moment in Debye |
| Etot_eV | Total single-point energy of the neutral molecule in eV |
| Etot_pos_eV | Total single-point energy of the positively charged molecule in eV |
| Etot_neg_eV | Total single-point energy of the negatively charged molecule in eV |
| ZPE_eV | Zero-point energy of the neutral molecule in eV |
| ZPE_pos_eV | Zero-point energy of the positively charged molecule in eV |
| ZPE_neg_eV | Zero-point energy of the negatively charged molecule in eV |
| aEA_eV | Adiabatic electron affinity in eV |
| aIP_eV | Adiabatic ionization potential in eV |
| n_rings | Number of rings |
| Erel_eV | Relative single-point energy of the neutral molecule (with respect to the lowest-energy isomer) in eV |
| HOMO_eV_corrected | xTB-to-DFT-corrected HOMO energy in eV |
| LUMO_eV_corrected | xTB-to-DFT-corrected LUMO energy in eV |
| GAP_eV_corrected | xTB-to-DFT-corrected HOMO-LUMO gap energy in eV |
| aIP_eV_corrected | xTB-to-DFT-corrected adiabatic ionization potential in eV |
| aEA_eV_corrected | xTB-to-DFT-corrected adiabatic electron affinity in eV |

### COMPAS-1D
This dataset contains ∼9k cata-condensed polybenzenoid hydrocarbons calculated at the B3LYP-D3BJ/def2-SVP level. The dataset contains the following data:

|  Data column header | Description |
|-------------|-------------|
| molecule | Identifier of the molecule (includes the molecular formula and a serial number) |
| smiles | SMILES string of the molecule |
| balaban_notation | annulation sequence after Balaban et al. notation |
| augmented_lalas | annulation sequence with angular directionality (aka augmented LALA string) |
| lalas | annulation sequence without angular directionality (aka LALA string) |
| HOMO_eV | HOMO energy in eV |
| LUMO_eV | LUMO energy in eV |
| GAP_eV | HOMO-LUMO gap in eV |
| Dipmom_Debye | Dipole moment in Debye |
| E_SCF_eV | SCF energy of the neutral molecule in eV |
| Etot_eV | Total single-point energy (SCF + dispersion correction) of the neutral molecule in eV |
| Etot_pos_eV | Total single-point energy of the positively charged molecule in eV |
| Etot_neg_eV | Total single-point energy of the negatively charged molecule in eV |
| aEA_eV | Adiabatic electron affinity in eV |
| aIP_eV | Adiabatic ionization potential in eV |
| n_rings | Number of rings |
| Erel_eV | Relative single-point energy of the neutral molecule (with respect to the lowest-energy isomer) in eV |

## How to cite this dataset
If you use the COMPAS database or any part of it, please cite the following:

For the COMPAS-1x and COMPAS-1D datasets:
A. Wahab, L. Pfuderer, E. Paenurk, and R. Gershoni-Poranne, The COMPAS Project: A Computational Database of Polycyclic Aromatic Systems. Phase 1: cata-condensed Polybenzenoid Hydrocarbons, DOI: 10.1021/acs.jcim.2c00503

## Support
For support or to report any issues with the COMPAS database, please contact: porannegroup /at/ technion.ac.il

## Roadmap
Several additional instalments are planned for the COMPAS Project. The next phases are currently in development and include: peri-condensed PBHs, poly(hetero)cyclic aromatic systems, and excited state PASs.

## Authors and acknowledgment
The COMPAS database was conceptualized by Prof. Renana Gershoni-Poranne and is constructed under her supervision. The following people contributed to data generation, curation, and organization: 
1. Ms. Alexandra Wahab (ETH Zurich)
2. Ms. Lara Pfuderer (ETH Zurich)
3. Dr. Eno Paenurk (ETH Zurich)

The invaluable assistance of the following people is gratefully acknowledged: Prof. Dr. Peter Chen, Dr. Alexandra Tsybizova. 

In addition, the financial support of the Branco Weiss Fellowship is acknowledged.

## License
The COMPAS database is provided free-of-charge and is intended to be a resource for the scientific community.
It is licensed under a CC-BY-NC-SA license. 

## Project status
The COMPAS Project is an ongoing project and the COMPAS database is under active development. Additional instalments will be reported in due course and the accompanying data will be deposited.
