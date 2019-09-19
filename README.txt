#This repository contains all code and data used for figure generation in analysis in Bitter et al. 2019

#All code is located in the Code Directory as iphyton notebooks and .html files
#Raw FastQ files are found in the NCBI SRA project -- 

#All data are subdivded into a Genetics and Phenotypes directory

#The Genetics/ directory contains:
##LarvalPopulations_AlleleFrequencyMatrix.csv – Allele frequency matrix generated from larval sample .vcf files and used to generate PCA figures in manuscript (Figures 3a and Figure 4a)
##Pools_ADTableMerged_2.txt – Table containing allelic depth at each variant site in the allele frequency matrix. This is used to generate the .sync files
##SyncFiles – Directory containing input files for PoPoolation (outlier loci identification) and  poolFstat 
##Fst - a directory containing FullDstbn_Fst.csv - FST values computed between starting larval population and larval populations within each treatment on Days 6, 26, and 43. Data used to generate Figure 3b. and D6_Fst.csv - Fst computed between all larval samples collected on Day 6. Data used to generate Figure 4b.




#The Phenotypes/ directory contains:
##LarvalSize_MetaData.csv – larval shell size measurements from larvae throughout experiment in each pH treatment. 
##SizeGroup_MetaData.csv – larval shell size measurements from size separated larvae.
##D26_Mortality.csv – larval counts used to generate reported mortality estimates between days 0 and 26 in each pH treatment.
##PilotSizeSep – data collected during pilot tests of size separation method. Data used to generate Supplementary Figure 2.
