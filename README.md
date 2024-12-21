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

Other files or information available upon request to [ajaffe@stanford.edu](mailto:ajaffe@stanford.edu). 
