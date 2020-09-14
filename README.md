# bioinformatics-tools
Collection of bioinformatic tools

## Sequencing Data Preprocess
- [FLASH](https://ccb.jhu.edu/software/FLASH/) - [commandLine] - FLASH (Fast Length Adjustment of SHort reads) is a very fast and accurate software tool to merge paired-end reads from next-generation sequencing experiments. FLASH is designed to merge pairs of reads when the original DNA fragments are shorter than twice the length of reads. The resulting longer reads can significantly improve genome assemblies. They can also improve transcriptome assembly when FLASH is used to merge RNA-seq data.


## CRISPR Target Deep Sequencing
- [CrispRVariants](http://www.bioconductor.org/packages/release/bioc/html/CrispRVariants.html) - [R] - CrispRVariants provides tools for analysing the results of a CRISPR-Cas9 mutagenesis sequencing experiment, or other sequencing experiments where variants within a given region are of interest. These tools allow users to localize variant allele combinations with respect to any genomic location (e.g. the Cas9 cut site), plot allele combinations and calculate mutation rates with flexible filtering of unrelated variants.
- [CRISP-ID](http://crispid.gbiomed.kuleuven.be) - [webtools] - CRISP-ID is a web application that allows the detection of the exact indel size and location of a CRISPR-Cas9 targeted region, based on direct Sanger sequencing. 
- [CRISPResso2](https://github.com/pinellolab/CRISPResso2) - [webtools, commandLine] - Analysis of deep sequencing data for rapid and intuitive interpretation of genome editing experiments. 1-aligns sequencing reads to a reference sequence; 2-quantifies insertions, mutations and deletions to determine whether a read is modified or unmodified by genome editing; 3-summarizes editing results in intuitive plots and datasets.
- [Microhomology-Predictor](http://www.rgenome.net/mich-calculator/) - [webtools] - Calculating microhomology-associated scores for all engineered nucleases [ZFNs, TALENs, RGENs (Cas9 RNA-guided endonucleases), etc.]

## The third generation sequencing
- [minimap2](https://github.com/lh3/minimap2) - [commandLine] - 
Minimap2 is a versatile sequence alignment program that aligns DNA or mRNA sequences against a large reference database. Typical use cases include: (1) mapping PacBio or Oxford Nanopore genomic reads to the human genome; (2) finding overlaps between long reads with error rate up to ~15%; (3) splice-aware alignment of PacBio Iso-Seq or Nanopore cDNA or Direct RNA reads against a reference genome; (4) aligning Illumina single- or paired-end reads; (5) assembly-to-assembly alignment; (6) full-genome alignment between two closely related species with divergence below ~15%.
- [longshot](https://github.com/pjedge/longshot) - [commandLine] - 
Longshot is a variant calling tool for diploid genomes using long error prone reads such as Pacific Biosciences (PacBio) SMRT and Oxford Nanopore Technologies (ONT). It takes as input an aligned BAM file and outputs a phased VCF file with variants and haplotype information. It can also genotype and phase input VCF files. It can output haplotype-separated BAM files that can be used for downstream analysis. Currently, it only calls single nucleotide variants (SNVs), but it can genotype indels if they are given in an input VCF.
## Structural Variation Detection
- [Snowman](https://github.com/broadinstitute/SnowmanSV) - [commandLine] - Snowman is a method for detecting structural variants in sequencing data using genome-wide local assembly. 
- [seeksv](https://github.com/qiukunlong/seeksv) - [commandLine] - an accurate tool for structural variation and virus integration detection.
- [Genomon SV](https://github.com/Genomon-Project/GenomonSV) - [commandLine] - Genomon SV is a software for detecting somatic structural variations from cancer genome sequencing data. Several characteristics of Genomon SV includes but not limited to.
- [BreakDancer](https://github.com/genome/breakdancer) - [commandLine] - BreakDancer-1.3.6, released under GPLv3, is a Cpp package that provides genome-wide detection of structural variants from next generation paired-end sequencing reads. It includes two complementary programs. BreakDancerMax predicts five types of structural variants: insertions, deletions, inversions, inter- and intra-chromosomal translocations from next-generation short paired-end sequencing reads using read pairs that are mapped with unexpected separation distances or orientation. 

