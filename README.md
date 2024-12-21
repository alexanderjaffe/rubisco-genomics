# rubisco-genomics

Code supporting "Abundant and metabolically flexible bacterial lineages underlie a vast  potential for rubisco-mediated carbon fixation in the dark ocean" (Jaffe et al., 2025).

## code

*`snakemake/` - Snakemake workflows for global metagenomic and metatranscriptomic analysis.
*`rubisco_superfamily.gpkg/` - Original graftM gpkg for extraction of rubisco superfamily sequences
*`notebooks/` - Code describing the main analyses and figure generation are available here in notebook format.
   * `deepeco-build-genome-set.ipynb` - Build genome set for the analysis by screening for rubisco superfamily. Assign quality information and taxonomy, curate rubisco-encoding scaffolds.
   * `deepeco-refine-rubisco.ipynb` - Classify and curate rubisco sequences within form groups.
   * `deepeco-metabolism-analyze.ipynb` - Perform functional annotation of genomes, curate annotations for a subset of metabolic genes.
   * `deepeco-metabolism-visualize.ipynb` - Visualize metabolic and taxonomic diversity (Figure 1).
   * `deepeco-diversity-local-public.ipynb` - Generate and analyze REO abundance information over the OC1703A transect (Figure 2).
   * `deepeco-diversity-global-public.ipynb` - Perform global abundance and biogeography analysis, in conjunction with snakemake/DNASnakefile. Generate figures 3 and 4.
   * `deepeco-transcriptomics-public.ipynb` - Perform genome-resolved metatranscriptomic analysis, in conjunction with snakemake/RNASnakefile. Generate figure 5.

## files

*`rubisco_superfamily.gpkg/' - Original graftM gpkg for rubisco classification.
*`hmms/` - Form-specific HMM profiles used for secondary rubisco classification.

## required software

*[graftM](https://github.com/geronimp/graftM)
*[kofam_scan](https://github.com/takaram/kofam_scan)
*[GTDBTk](https://github.com/Ecogenomics/GTDBTk)
*[CheckM](https://github.com/Ecogenomics/CheckM)
*[dRep](https://github.com/MrOlm/drep)
*[DIAMOND](https://github.com/bbuchfink/diamond)
*[prodigal](https://github.com/hyattpd/Prodigal)
*[HMMER](https://github.com/EddyRivasLab/hmmer)
*[USEARCH](https://www.drive5.com/usearch/)
*[MAFFT](https://github.com/GSLBiotech/mafft)
*[FastTreeMP](https://morgannprice.github.io/fasttree/)
*[BLAST](https://blast.ncbi.nlm.nih.gov/doc/blast-help/downloadblastdata.html)
*[bowtie2](https://github.com/BenLangmead/bowtie2)
*[samtools](https://github.com/samtools/samtools)
*[CoverM](https://github.com/wwood/CoverM)
*[Snakemake](https://github.com/snakemake/snakemake)
*[parallel-fastq-dump](https://github.com/rvalieris/parallel-fastq-dump)
*[BBTools/BBDuk](https://jgi.doe.gov/data-and-tools/software-tools/bbtools/bb-tools-user-guide/bbduk-guide/)
*[inStrain](https://github.com/MrOlm/inStrain)

Other files or information available upon request to [ajaffe@stanford.edu](mailto:ajaffe@stanford.edu). 
