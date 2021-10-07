---
title: October 2017 Tool Shed contributions
---

[<img class="float-right" src="/images/galaxy-logos/galaxy-toolshed-300.png" alt="Galaxy ToolShed" width="180">](http://toolshed.g2.bx.psu.edu/)

Tools contributed to the Galaxy Project [ToolShed](http://toolshed.g2.bx.psu.edu/) in [October 2017](/galaxy-updates/2017-11/).

* [All monthly summaries](/toolshed/contributions/)

## New Tools

* *From [iuc](https://toolshed.g2.bx.psu.edu/view/iuc):*
   * [package_blast_plus_2_7_1](https://toolshed.g2.bx.psu.edu/view/iuc/package_blast_plus_2_7_1):  NCBI BLAST+ 2.7.1 (binaries only). This Tool Shed package is intended to be used as a dependency of the Galaxy wrappers for NCBI BLAST+ and any other tools which call the BLAST+ binaries internally.    Note that for compatibility with BioConda, internally this is now called "blast" rather than "blast+" as in the older Galaxy BLAST+ packages.
* *From [nml](https://toolshed.g2.bx.psu.edu/view/nml):*
   * [fasta2bed](https://toolshed.g2.bx.psu.edu/view/nml/fasta2bed):  Convert multiple fasta file into tabular bed file format. Simple script to convert a multiple fasta file into a bed file format where the coordinators for each record is from base pair 1 till end of contig.
   * [fastqc_stats](https://toolshed.g2.bx.psu.edu/view/nml/fastqc_stats):  Summary multiple FastQC into a single tabular line report. Tool will attempt to generate an one line tabular report per sample based on forward and reverse FastQC reports and raw fastqs.
   * [filter_spades_repeats](https://toolshed.g2.bx.psu.edu/view/nml/filter_spades_repeats):  Remove short and repeat contigs/scaffolds. Using the output of SPAdes (a fasta and a stats file, either from contigs or scaffolds), it filters the fasta files, discarding all sequences that are under a given length or under a calculated coverage. Repeated contigs are detected based on coverage.
* *From [vmarcon](https://toolshed.g2.bx.psu.edu/view/vmarcon):*
   * [plot_pca](https://toolshed.g2.bx.psu.edu/view/vmarcon/plot_pca):  Simple PCA plot. 
* *From [testtool](https://toolshed.g2.bx.psu.edu/view/testtool):*
   * [accuracy](https://toolshed.g2.bx.psu.edu/view/testtool/accuracy):  Tool allow us to build 5 different prediction models: LDA, CART, kNN, SVM, RF (and choose the best one). 
   * [survival](https://toolshed.g2.bx.psu.edu/view/testtool/survival):  Contains the core survival analysis routines, including definition of Surv objects. 
* *From [bgruening](https://toolshed.g2.bx.psu.edu/view/bgruening):*
   * [augustus_training](https://toolshed.g2.bx.psu.edu/view/bgruening/augustus_training):  Train Augustus tool from the augustus package. AUGUSTUS is a program that predicts genes in eukaryotic genomic sequences.    http://bioinf.uni-greifswald.de/augustus/.
* *From [eschen42](https://toolshed.g2.bx.psu.edu/view/eschen42):*
   * [w4mjoinpn](https://toolshed.g2.bx.psu.edu/view/eschen42/w4mjoinpn):  Join positive- and negative-mode W4M datasets. Join positive and negative ionization-mode W4M datasets for the same samples.
   * [w4mcorcov](https://toolshed.g2.bx.psu.edu/view/eschen42/w4mcorcov):  OPLS-DA Contrasts of Univariate Results. SIMCA OPLS-DA S-PLOT "work-alike" for W4M data.
* *From [refinery-platform](https://toolshed.g2.bx.psu.edu/view/refinery-platform):*
   * [split_paired_collection](https://toolshed.g2.bx.psu.edu/view/refinery-platform/split_paired_collection):  Split the elements of a Paired Dataset Collection into two distinct outputs. Splits the elements of a Paired Dataset Collection into two distinct outputs  Input: Paired Dataset Collection  Outputs: Two files corresponding to the two elements of said collection.
* *From [jnavarro](https://toolshed.g2.bx.psu.edu/view/jnavarro):*
   * [creatematrix](https://toolshed.g2.bx.psu.edu/view/jnavarro/creatematrix):  createMatrix. createMatrix.
* *From [dktanwar](https://toolshed.g2.bx.psu.edu/view/dktanwar):*
   * [test_r](https://toolshed.g2.bx.psu.edu/view/dktanwar/test_r):  testing. 
   * [removesnp](https://toolshed.g2.bx.psu.edu/view/dktanwar/removesnp):  Tool to remove reads with certain number of mismatches from SAM alignment file. 
* *From [mingchen0919](https://toolshed.g2.bx.psu.edu/view/mingchen0919):*
   * [rmarkdown_bdss_client](https://toolshed.g2.bx.psu.edu/view/mingchen0919/rmarkdown_bdss_client):  R Markdown based bdss_client wrapper. Download and extract reads in fastq/fasta format from NCBI SRA with the Big Data Smmrt Socket (BDSS) client and output a list or list:paired dataset collection.
* *From [bornea](https://toolshed.g2.bx.psu.edu/view/bornea):*
   * [plot_force](https://toolshed.g2.bx.psu.edu/view/bornea/plot_force):  Plot Force. Plot Force.
   * [plot_adjacency](https://toolshed.g2.bx.psu.edu/view/bornea/plot_adjacency):  Plot Adjacency. Plot Adjacency.
   * [plot_force_ev](https://toolshed.g2.bx.psu.edu/view/bornea/plot_force_ev):  Plot Force EV. Plot Force EV.
   * [network_attributes](https://toolshed.g2.bx.psu.edu/view/bornea/network_attributes):  This function takes in a SIF formatted dataframe and returns a node attribute dataframe. This function takes in a SIF formatted dataframe and returns a node attribute dataframe.
   * [plot_edge_bundling](https://toolshed.g2.bx.psu.edu/view/bornea/plot_edge_bundling):  Plot Edge Bundling. Plot Edge Bundling.
* *From [iuc](https://toolshed.g2.bx.psu.edu/view/iuc):*
   * [colibread_takeabreak](https://toolshed.g2.bx.psu.edu/view/iuc/colibread_takeabreak):  TakeABreak (from the Colib'read tool suite). Kissplice, DiscoSNP and TakeABreak perform de novo variant identification and quantification. For these tools the general approach consists in 1) defining a model for the seeked elements; 2) detecting in one or several NGS datasets those elements that fit the model; 3) outputting those together with a score and their genomic neighborhood.  Mapsembler focuses on sequences of interest within a micro targeted assembly, LorDec uses short reads for correcting third generation long reads, and finally Commet is dedicated to the comparison of numerous metagenomic read sets.
   * [colibread_kissplice](https://toolshed.g2.bx.psu.edu/view/iuc/colibread_kissplice):  KisSplice (from the Colib'read tool suite). Kissplice, DiscoSNP and TakeABreak perform de novo variant identification and quantification. 
   * [colibread_mapsembler2](https://toolshed.g2.bx.psu.edu/view/iuc/colibread_mapsembler2):  Mapsembler2 (from the Colib'read tool suite). Kissplice, DiscoSNP and TakeABreak perform de novo variant identification and quantification. 
   * [colibread_lordec](https://toolshed.g2.bx.psu.edu/view/iuc/colibread_lordec):  Lordec (from the Colib'read tool suite). Kissplice, DiscoSNP and TakeABreak perform de novo variant identification and quantification. 
   * [colibread_commet](https://toolshed.g2.bx.psu.edu/view/iuc/colibread_commet):  Commet (from the Colib'read tool suite). Kissplice, DiscoSNP and TakeABreak perform de novo variant identification and quantification. For these tools the general approach consists in 1) defining a model for the seeked elements; 2) detecting in one or several NGS datasets those elements that fit the model; 3) outputting those together with a score and their genomic neighborhood.  Mapsembler focuses on sequences of interest within a micro targeted assembly, LorDec uses short reads for correcting third generation long reads, and finally Commet is dedicated to the comparison of numerous metagenomic read sets.
   * [colibread_discosnp_pp](https://toolshed.g2.bx.psu.edu/view/iuc/colibread_discosnp_pp):  DiscoSnp++ (from the Colib'read tool suite). Kissplice, DiscoSNP and TakeABreak perform de novo variant identification and quantification. For these tools the general approach consists in 1) defining a model for the seeked elements; 2) detecting in one or several NGS datasets those elements that fit the model; 3) outputting those together with a score and their genomic neighborhood.  Mapsembler focuses on sequences of interest within a micro targeted assembly, LorDec uses short reads for correcting third generation long reads, and finally Commet is dedicated to the comparison of numerous metagenomic read sets.
   * [crossmap_bam](https://toolshed.g2.bx.psu.edu/view/iuc/crossmap_bam):  Wrapper for the CrossMap tool suite: CrossMap BAM. CrossMap is versatile tool to convert genome coordinates or annotation files between genome  assemblies. It supports mostly commonly used file types, including BAM, BED,BigWig, GFF,  GTF, SAM, Wiggle, and VCF formats. For large plain text file types, such as BED, GFF, GTF  and VCF, reading from remote servers and file compression are supported.
   * [crossmap_bw](https://toolshed.g2.bx.psu.edu/view/iuc/crossmap_bw):  Wrapper for the CrossMap tool suite: CrossMap BigWig. 
   * [crossmap_bed](https://toolshed.g2.bx.psu.edu/view/iuc/crossmap_bed):  Wrapper for the CrossMap tool suite: CrossMap BED. 
   * [crossmap_vcf](https://toolshed.g2.bx.psu.edu/view/iuc/crossmap_vcf):  Wrapper for the CrossMap tool suite: CrossMap VCF. 
   * [crossmap_wig](https://toolshed.g2.bx.psu.edu/view/iuc/crossmap_wig):  Wrapper for the CrossMap tool suite: CrossMap Wig. 
   * [snap_training](https://toolshed.g2.bx.psu.edu/view/iuc/snap_training):  Train SNAP tool from the snap package. SNAP is a general purpose gene finding program suitable for both eukaryotic and prokaryotic genomes.    https://github.com/KorfLab/SNAP.
   * [snap](https://toolshed.g2.bx.psu.edu/view/iuc/snap):  SNAP tool from the snap package. SNAP is a general purpose gene finding program suitable for both eukaryotic and prokaryotic genomes.    https://github.com/KorfLab/SNAP.
   * [maker_map_ids](https://toolshed.g2.bx.psu.edu/view/iuc/maker_map_ids):  Map annotation ids tool from the maker package. MAKER is a portable and easily configurable genome annotation pipeline.  Its purpose is to allow smaller eukaryotic and prokaryotic genome projects to independently annotate their genomes and to create genome databases.
   * [shovill](https://toolshed.g2.bx.psu.edu/view/iuc/shovill):  Faster de novo assembly pipeline based around Spades. The SPAdes genome assembler has become the de facto standard de novo genome assembler  for Illumina whole genome sequencing data of bacteria and other small microbes.  SPAdes was a major improvement over previous assemblers like Velvet,  but it can be very slow to run and does not handle overlapping paired-end reads well.    Shovill is a pipeline which uses SPAdes at its core, but alters the steps before and after  the primary assembly step to get near-identical results in far less time.
   * [bio_hansel](https://toolshed.g2.bx.psu.edu/view/iuc/bio_hansel):  Heidelberg and Enteritidis SNP Elucidation. bio_hansel - Heidelberg And eNteritidis Snp ELucidation - Subtype Salmonella enterica subsp. enterica serovar Heidelberg and Enteritidis genomes using in-silico 33 bp k-mer SNP subtyping schemes developed by Genevieve Labbe et al.
   * [coverage_report](https://toolshed.g2.bx.psu.edu/view/iuc/coverage_report):  Generate Detailed Coverage Report from BAM file. Generate Coverage reports for Gene Panel data, including per gene and per exon plots. Uses a bam file and assay file (BED). Also usable for WES data, for a global overview o assay performance  % captured,  on/off target, median coverage, % 0.2*Average coverage etc.
   * [multiqc](https://toolshed.g2.bx.psu.edu/view/iuc/multiqc):  MultiQC aggregates results from bioinformatics analyses across many samples into a single report. MultiQC searches a given directory for analysis logs and compiles a HTML report.   It's a general use tool, perfect for summarising the output from numerous bioinformatics tools.
   * [data_manager_fetch_busco](https://toolshed.g2.bx.psu.edu/view/iuc/data_manager_fetch_busco):  Contains a data manager that defines and populates the busco tool data table. Download BUSCO reference datasets and add their paths to a data table.
   * [migmap](https://toolshed.g2.bx.psu.edu/view/iuc/migmap):  mapper for full-length T- and B-cell repertoire sequencing. A smart wrapper for IgBlast V-(D)-J mapping tool designed to facilitate analysis immune receptor libraries profiled using high-throughput sequencing.
   * [orthofinder_onlygroups](https://toolshed.g2.bx.psu.edu/view/iuc/orthofinder_onlygroups):  OrthoFinder OnlyGroups tool for orthogroups inference. OrthoFinder is a fast, accurate and comprehensive analysis tool for comparative genomics. It finds orthologues and orthogroups infers gene trees for all orthogroups and infers a rooted species tree for the species being analysed. OrthoFinder also provides comprehensive statistics for comparative genomic analyses.
   * [maker](https://toolshed.g2.bx.psu.edu/view/iuc/maker):  Maker tool from the maker package. MAKER is a portable and easily configurable genome annotation pipeline.  Its purpose is to allow smaller eukaryotic and prokaryotic genome projects to independently annotate their genomes and to create genome databases.
* *From [artbio](https://toolshed.g2.bx.psu.edu/view/artbio):*
   * [cherry_pick_fasta](https://toolshed.g2.bx.psu.edu/view/artbio/cherry_pick_fasta):  Pick fasta sequence with specific header content. This tool takes a collection of fasta sequences as an input and select those that satisfy a query match in their header/name  A subset of fasta sequence satisfying the query is returned.
   * [blastparser_and_hits](https://toolshed.g2.bx.psu.edu/view/artbio/blastparser_and_hits):  Parse blast outputs and compile hits. This tool is part of the visitor2 toolsuite.  The tool parses blastn or blastx outputs and organizes hits to subjects, with various coverage informations  It also outputs query hits sorted by their alignment to blast subjects, so that they can be picked for subsequent CAP3 assembly.
   * [oases](https://toolshed.g2.bx.psu.edu/view/artbio/oases):  Short read assembler. Oases use velvet to assemble sequence reads. Here the tool is used for short read assembly.
   * [bamparse](https://toolshed.g2.bx.psu.edu/view/artbio/bamparse):  Generates hit count lists from bam alignments. Generates hit count lists from bam alignments.
   * [blast_to_scaffold](https://toolshed.g2.bx.psu.edu/view/artbio/blast_to_scaffold):  Generate DNA scaffold from blastn or tblastx alignments of Contigs. This tool start from DNA contigs that aligned to a subject DNA sequence through blastn or tblastx.  The contigs must be provided in fasta format. The blastn or tblastx output must be tabular, the 12 standard column plus column 13 with the length of the blastn or tblastx subject.  The sequence used to BLAST (blastn or tblastx) the contigs must be provided to serve as a guide to the final assembly  The final assembly is a DNA sequence.  Nucleotides of the guide sequence which were not covered by contigs are in small letters in the output assembly.
   * [blastx_to_scaffold](https://toolshed.g2.bx.psu.edu/view/artbio/blastx_to_scaffold):  Generate DNA scaffold from blastx alignment of Contigs. This tool start from DNA contigs that aligned to a subject protein sequence through blastx.  The contigs must be provided in fasta format. The blastx output must be tabular, the 12 standard column plus column 13 with the length of the blastx subject.  The final scaffold is a DNA sequence.  Sequences of the subject protein which were not aligned to the contigs are replaced by Ns in this scaffold.
   * [blast_unmatched](https://toolshed.g2.bx.psu.edu/view/artbio/blast_unmatched):  Extract unmatched query sequences from blast. Extract unmatched query sequences that remained unmatched after blast.
* *From [romaingred](https://toolshed.g2.bx.psu.edu/view/romaingred):*
   * [pirna_pipeline](https://toolshed.g2.bx.psu.edu/view/romaingred/pirna_pipeline):  A pipeline to analyse smallRNA sequencing and particularly piRNAs. 
* *From [rnateam](https://toolshed.g2.bx.psu.edu/view/rnateam):*
   * [mqc](https://toolshed.g2.bx.psu.edu/view/rnateam/mqc):  Ribosome profiling mapping quality control tool. MappingQC is a tool to easily generate some figures which give a nice overview of the quality of the mapping of ribosome profiling data. More specific, it gives an overview of the P site offset calculation, the gene distribution and the metagenic classification. Furthermore, MappingQC does a thorough analysis of the triplet periodicity and the linked triplet phase (typical for ribosome profiling) in the canonical transcript of your data. Especially, the link between the phase distribution and the RPF length, the relative sequence position and the triplet identity are taken into account.
   * [hmmcv](https://toolshed.g2.bx.psu.edu/view/rnateam/hmmcv):  Wrapper for application hmmcv of the cmv suite. cmv is a collection of tools for the visualisation of Hidden Markov Models (HMMV)  and RNA-family models (CMV). Moreover it can visualise comparisons of these models (HMMCV,CMCV),  and annotate linked regions in the structural alignments they were constructed from and via,  3rd party tools, in their consensus secondary structure.
   * [cmcv](https://toolshed.g2.bx.psu.edu/view/rnateam/cmcv):  Wrapper for application CMCV of the cmv suite. cmv is a collection of tools for the visualisation of Hidden Markov Models (HMMV)  and RNA-family models (CMV). Moreover it can visualise comparisons of these models (HMMCV,CMCV),  and annotate linked regions in the structural alignments they were constructed from and via,  3rd party tools, in their consensus secondary structure.
   * [cmv](https://toolshed.g2.bx.psu.edu/view/rnateam/cmv):  Wrapper for application cmv of the cmv suite. cmv is a collection of tools for the visualisation of Hidden Markov Models (HMMV)  and RNA-family models (CMV). Moreover it can visualise comparisons of these models (HMMCV,CMCV),  and annotate linked regions in the structural alignments they were constructed from and via,  3rd party tools, in their consensus secondary structure.
   * [hmmv](https://toolshed.g2.bx.psu.edu/view/rnateam/hmmv):  Wrapper for application hmmv of the cmv suite. cmv is a collection of tools for the visualisation of Hidden Markov Models (HMMV)  and RNA-family models (CMV). Moreover it can visualise comparisons of these models (HMMCV,CMCV),  and annotate linked regions in the structural alignments they were constructed from and via,  3rd party tools, in their consensus secondary structure.