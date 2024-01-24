# ElbeEstuarineZander
A repository for the analysis of tissue-specific transcriptomes and 16S data for Elbe estuarine Sander lucioperca

The Analysis splits into 5 parts

1: RNAseq & 16S Dataprocessing-Pipeline used on  Linux-HPC: SL_Linux_16.01.2024.Rmd

2: Bacteria Metabarcoding Analysis based in V3V4 16S in R: SL_16S_16.01.24_Paper.Rmd

3: Transcriptome analysis for tissue specific RNAseq in R: SL_RNA_16.01.24_Paper.Rmd

4 & 5: Network Analysis Pipeline in R: SL_WGCNA_Part1_16.01.2024_Paper.Rmd & SL_WGCNA_Part2_16.01.2024_Paper.Rmd

Additional files: 
Every .rmd is accompanied by a markdown .html that includes a subset of plots and results

SL_Functions_16.01.24_Paper.Rmd is a long Functions-File that has to be saved in the R-directory and loaded in section ## 1.2 Functions in every .rmd

There is a packrat private R environment buldle that allows you to restore the packages used in the analysis: ElbeEstuarineZander-2024-01-23.tar.gz that has to be downloadded from 
https://gitlab.rrz.uni-hamburg.de/ElbeEstuarineZander

Sequence data are deposited in the ENA Sequence Read archive under study PRJEB71116

