SLiM script used to generate figures in Negm & Veller, "The effect of long-range linkage disequilibrium on allele-frequency dynamics under stabilizing selection".

There are several options:
"map": The loci underlying variation in the trait can be unlinked (option "unlinked"), or they can lie along the linkage map of humans (option "human") or Drosophila melanogaster (option "Dmel").
"MAFs_setting": The minor allele frequencies can be constant, at 0.2, across loci (option "constant") or they can vary across loci, chosen independently from a uniform distribution on [0.1, 0.3] (option "variable").
"effectSizes_setting": The effect sizes of alleles can be constant, at 1, across loci (option "constant") or they can vary across loci, chosen independently from a normal distribution with mean zero and variance 1 (option "variable").

For Figure 1 in Negm & Veller, map=unlinked, MAFs_setting=constant, effectSizes_setting=constant.
For Figure 2A, map=human, MAFs_setting=constant, effectSizes_setting=constant.
For Figures 2B and 3, map=Dmel, MAFs_setting=constant, effectSizes_setting=constant.
For Figure S2, map=unlinked, MAFs_setting=variable, effectSizes_setting=variable.
For Figure S3, map=Dmel, MAFs_setting=variable, effectSizes_setting=variable.
For Figures S1 and S4, map=human, MAFs_setting=variable, effectSizes_setting=variable.
