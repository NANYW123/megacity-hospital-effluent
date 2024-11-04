##### Deciphering antibiotic resistance genes and plasmids in pathogenic bacteria from 166 hospital effluents in Shanghai, China.

This directory contains scripts related to the manuscript "Deciphering antibiotic resistance genes and plasmids in pathogenic bacteria from 166 hospital effluents in Shanghai, China". 
Before running, you must ensure that all required softwares and databases are installed successfully.

###### How to Reference?  
If you have used this script in your research, please use the following link for references to our script: https://github.com/NANYW123/megacity-hospital-effluent.git.
Please also cite the corresponding software.

### Software and database installation

Most of the softwares can be installed through [conda](https://www.anaconda.com/products/individual). The installation method refer to the manual of each software. The following published software is used in our script.
The name, version and availablity of the software are as follows:  

|Software|Availability|
|:--------|:-----------|
|fastp v0.23.4 |(https://github.com/OpenGene/fastp) |
|MetaPhlAn4 v4.1.1 |(https://github.com/biobakery/MetaPhlAn)|
|ARGs-OAP3 v3.1.1 |(https://github.com/alienzj/args_oap)|
|BLAST (v2.10.1+)| ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/|
|MEGAHIT v1.2.9 |(https://github.com/voutcn/megahit)|
|SCAPP v0.1.4 |(https://github.com/Shamir-Lab/SCAPP)|
|ResFinder (v4.0) | https://bitbucket.org/genomicepidemiology/resfinder_db/src/master/|
|MOB-suite v3.1.9 |https://github.com/phac-nml/mob-suite|
|PlasmidFinder (v2.0.1) | https://bitbucket.org/genomicepidemiology/plasmidfinder_db/src/master/|
|metaWRAP v1.3.2 |(https://github.com/bxlab/metaWRAP)|
|CheckM |(https://github.com/Ecogenomics/CheckM)|
|CompareM v0.1.2 |(https://github.com/dparks1134/CompareM)|
|dRep v3.4.2 |(https://github.com/MrOlm/drep)|
|PhyloPhlAn v3.0.60 |(https://github.com/biobakery/phylophlan)|
|ABRicate (v1.0.1) | https://github.com/tseemann/abricate|
|ResFinder v4.0 |(https://bitbucket.org/genomicepidemiology/resfinder/src/master/)|
|RGI v6.0.3 |(https://github.com/arpcard/rgi)|
|VFDB (2022) | http://www.mgc.ac.cn/VFs/download.htm|
|MobileElementFinder v1.0.3 (https://bitbucket.org/mhkj/mge_finder/src/master/)|
|Prokka (v1.14.5) | https://github.com/tseemann/prokka|


### Note: The version are only the version used in the paper, most of database are constantly updated.

The software parameters refer to our previous article “The multi-kingdom microbiome catalog of the chicken gastrointestinal tract”. The source code used for the CMKMC analysis in this study is available at https://github.com/NANYW123/Chicken-CMKMC.git.

### OVERVIEW OF PIPELINE

The scripts of whole-genome sequencing analysis are placed in "[Pipeline](https://github.com/NANYW123/megacity-hospital-effluent.git)" directory. There are six steps in the pipeline, Drivers and landscape of antibiotic resistome, virulome and mobilome in the Salmonella genome database of over 8,000 isolates in China.


## Limitations
 
This workflow was designed specifically for "Deciphering antibiotic resistance genes and plasmids in pathogenic bacteria from 166 hospital effluents in Shanghai, China"; editing and revisions might be required before applying to other projects.
