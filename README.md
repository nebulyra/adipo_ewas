# Adipokine EWAS Meta-analysis
This repository contains all scripts required to reproduce findings in our paper "DNA methylation of genes involved in lipid metabolism drives adiponectin levels and metabolic disease".

The scripts are, in order:
1. Perform an EWAS on adiponectin levels within the LLS cohort
2. Perform an EWAS on leptin levels within the LLS cohort
3. Combine summary statistics from the three participating cohorts (LLS, KORA, TwinsUK, LLD, and SHIP-TREND)
4. Perform QC on the combined dataset
5. Adjust for bias and inflation in the test statistics using ```bacon```
6. Re-check quality of data following adjustment
7. Perform an EWAS meta-analysis in ```METAL```
8. Combine results from all meta-analysed models
9. Perform sensitivity analyses for smoking status, extended cell counts predicted using DNAm data, and BMI
10. Identify distinct genomic loci
11. Create a bidirectional Manhattan plot for both adipokines and a scatter plot of effect sizes at significant CpGs
12. Perform a test for enrichment of previous associations in the results
13. Perform a test for enrichment of chromatin states in the results using a PBMC reference epigenome
14. Perform a test in ```HOMER``` for enrichment of transcription factor binding sites in the results
15. Perform integrative analyses in BIOS to identify cis-eQTMs in blood
16. Overrepresentation analysis of genes linked to an adipokine-associated CpG for adiponectin and leptin
17. Perform two-sample Mendelian randomization on the effects of DNAm on each adipokine and vice versa
18. Perform triangulation analysis on the effects of DNAm on each adipokine and vice versa
19. Use publicly available adipocyte data to link cg02235049 and ADIPOQ expression
20. Perform summary-based Mendelian randomization on the effects of DNAm on metabolic traits and vice versa
