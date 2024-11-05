# _Kudoa_ genomes

This repository contains data associated with: Weber CC et al., [_Kudoa genomes from contaminated hosts reveal extensive gene order conservation and rapid sequence evolution_](https://www.biorxiv.org/content/10.1101/2024.11.01.621499v1).

## Genomic data

Some of the data are still making their way into public repositories. In the meantime, the assemblies are available [here](./genome_assemblies/).

### Public release

| Species | ToLID | Biosample | Primary assembly| Alternate haplotype | Mitochondrion | Assembly method |
| -- | -- | --|--|--|--| -- |
| _Kudoa neothunni_ | jmKudNeot1 | [SAMEA115884706](https://www.ebi.ac.uk/ena/browser/view/SAMEA115884706) | [PRJEB82086](https://www.ebi.ac.uk/ena/browser/view/PRJEB82086) | [PRJEB82087](https://www.ebi.ac.uk/ena/browser/view/PRJEB82087) | _see primary_ | hifiasm-meta |
| _Kudoa sp. trachurus_ | jmKudSpea1 | [SAMEA116001081](https://www.ebi.ac.uk/ena/browser/view/SAMEA116001081) | [PRJEB80899](https://www.ebi.ac.uk/ena/browser/view/PRJEB80899) | [PRJEB80900](https://www.ebi.ac.uk/ena/browser/view/PRJEB80900) | [PRJEB81409](https://www.ebi.ac.uk/ena/browser/view/PRJEB81409) | [read_VAE*](https://github.com/CobiontID/read_VAE), wtdbg2 |


 *See: Weber CC (2024) [_Disentangling cobionts and contamination in long-read genomic data using sequence composition_](https://doi.org/10.1093/g3journal/jkae187)

## Gene annotation

Annotations were produced with BRAKER3 using protein hints from free-living Cnidarians and _K. iwatai_, and are available [here](./gene_annotations/).


## Additional information
### Embedding tools used for assemblies
- https://github.com/CobiontID/HiC_network
- https://github.com/CobiontID/read_VAE
### Identification of _Kudoa_ ribosomal SSU
- https://github.com/CobiontID/MarkerScan
