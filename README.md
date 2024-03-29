## Scripts of Ordon, Thouin, *et. al*, Simultaneous tracking of near-isogenic bacterial strains in synthetic Arabidopsis microbiota by chromosomally-integrated barcodes. (https://doi.org/10.1101/2023.04.20.537712)

These scripts are made available to facilitate the reproducibility of our research. If you re-use any or part of this code, please reference with comments and cite our paper.

---------------------------

### Accession number and desing files:

Raw *16S* rRNA amplicon reads were deposited in the European Nucleotide Archive (ENA) under the accession number PRJEB61076.

The design files for the gnotobiotic SynCom experiment and the validation of the oligonucleotides:
- [MoBacTag_V2_design.txt](https://github.com/thouinjulien/MoBacTag/blob/main/MoBacTag_V2_design.txt)
- [Validation-Primers_design.txt](https://github.com/thouinjulien/MoBacTag/blob/main/Validation-Primers_design.txt)

The design file for the MoBacTag-labeled *Rhizobium* R13C and R13D in resident microbial communities of two soil types and a peat substrate:
- [MoBacTag_soil_design.txt](https://github.com/thouinjulien/MoBacTag/blob/main/MoBacTag_soil_design.txt)

---------------------------

### Scripts used for processing data, creating the figures and performing the statistical analysis reported in the manuscript:

Raw data corresponding to the SynCom experiment or the validation of the oligonucleotides were processed as described in the manuscript and using the script [syncom_ASV-table.sh](https://github.com/thouinjulien/MoBacTag/blob/main/syncom_ASV-table.sh).

Every plots were generated with R and each script is named regarding the figure from the publication.
The scripts to generate the plots from the figures are listed below:

Figure 1: 
- [Figure1C.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure1C.R)

Figure 2: 
- [Figure2B-C.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure2B-C.R)
- [Figure2D-F.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure2D-F.R)

Figure 4:
- [Figure4.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure4.R)

Figure 5: 
- [Figure5A-C.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure5A-C.R)
- [Figure5D-G.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure5D-G.R)

Figure 6:
- [Figure6.R](https://github.com/thouinjulien/MoBacTag/blob/main/Figure6.R)

Extended Data Figure 3:
- [Extended_Data_Figure3A-B.R](https://github.com/thouinjulien/MoBacTag/blob/main/Extended_Data_Figure3A-B.R)
- [Extended_data_fig 3C-D.R](https://github.com/thouinjulien/MoBacTag/blob/main/Extended_data_fig%203C-D.R)

Extended Data Figure 6:
- [Extended_data_Fig_6.R](https://github.com/thouinjulien/MoBacTag/blob/main/Extended_data_Fig_6.R)

Extended Data Figure 7:
- [Extended_Data_Figure_7.R](https://github.com/thouinjulien/MoBacTag/blob/main/Extended_Data_Figure_7.R)

---------------------------

### Supplementary data:

Data extracted without any scripts are listed below: 
- [frequency_primer_per_position.txt](https://github.com/thouinjulien/MoBacTag/blob/main/frequency_primer_per_position.txt)
- [WCS358_16SvsBC.txt](https://github.com/thouinjulien/MoBacTag/blob/main/WCS358_16SvsBC.txt)
- [MultipleBarcodes.txt](https://github.com/thouinjulien/MoBacTag/blob/main/MultipleBarcodes.txt)
- [Extended_Data_Fig_3cd.txt](https://github.com/thouinjulien/MoBacTag/blob/main/Extended_Data_Fig_3cd.txt)
- [OD600_WCS358_PQQ_extended_data_fig_6.txt](https://github.com/thouinjulien/MoBacTag/blob/main/OD600_WCS358_PQQ_extended_data_fig_6.txt)

---------------------------

### Authors

Jana Ordon (ordon@mpipz.mpg.de)

Julien Thouin (thouin@mpipz.mpg.de)
