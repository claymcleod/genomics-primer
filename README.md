This repository contains all of the resources I have found helpful in studying genomics from the ground up.

## Introduction
    
1. [A Brief Guide to Genomics][1] by the National Human Genome Research Institute 
2. [Overview of genomic file formats][10]. Introduction to common file types for genomics.
3. [FastQ file specification][11]. Illumina raw data format specification. In general, this is thought to be the industry standard.
4. [SAM/BAM file specification][9]. This is the industry standard file-type for *aligned* sequence data. Know this format like the back of your hand.

## Useful software

* [Samtools][5]: manipulate and perform common tasks for SAM/BAM/CRAM files.
* [BWA aligner][4]: Industry standard WGS/WXS aligner
* [STAR aligner][6]: Industry standard Transcriptome aligner
* [Picard][8]: Swiss-army knife of genomics
* [GATK][12]: Genome Analysis Toolkit, industry standard variant caller.
* [FastQC][13]: Industry standard raw data quality check software.
* [htseq][7]: Useful for counting gene expression

## Data sources

### Raw data

* [1000 genomes][22]: The "thousand genome project" is a well-known project that houses raw/variant data from 1000 people across the world.
* [dbGaP][14]: NIH (U.S. based) genomics repository
* [EGA][15]: EBI (European based) genotype-phenotype repository

## Variation data

### General purpose

* [dbSNP][16]: de-facto single nucleotide polymorphism database. Mostly research oriented.
* [OMIM][18]: The "Online Mendelian Inheritance in Man" is a catalog that maps genotypes -> phenotypes. A great resource for handcrafting articles and literature curation.

### Clinical significance

* [ClinVar][17]: clinical significance of variations for humans.
* [PolyPhen-2][19]: The "Polymorphism Phenotyping v2" tool attempts to predict the functional/structural effects of a variant on a human protein.
* [SIFT][20]: The SIFT tool attempts to predict whether an amino acid substitution affects protein function.
* [FATHMM][21]: FATHMM stands for "functional analysis though hidden markov models". This tool attempts to predict the functional affect of a variant on the resulting protein.

## Data science applied to genomics 

* [Machine Learning in Genomic Medicine][3]
* [Machine Learning Applications in Genetics and Genomics][2]
    
[1]: https://www.genome.gov/18016863/a-brief-guide-to-genomics/
[2]: http://www.nature.com/nrg/journal/v16/n6/full/nrg3920.html
[3]: http://www.psi.toronto.edu/publications/2015/Machine%20Learning%20in%20Genomic%20Medicine-%20A%20Review%20of%20Computational%20Problems%20and%20Data%20Sets.pdf
[4]: http://bio-bwa.sourceforge.net/
[5]: http://samtools.github.io/
[6]: https://github.com/alexdobin/STAR
[7]: http://www-huber.embl.de/HTSeq/doc/index.html#
[8]: https://broadinstitute.github.io/picard/ 
[9]: https://samtools.github.io/hts-specs/SAMv1.pdf
[10]: https://genome.ucsc.edu/ENCODE/fileFormats.html#FASTQ
[11]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2847217/
[12]: https://software.broadinstitute.org/gatk/
[13]: http://www.bioinformatics.babraham.ac.uk/projects/fastqc/
[14]: https://www.ncbi.nlm.nih.gov/gap
[15]: https://www.ebi.ac.uk/ega/home
[16]: https://www.ncbi.nlm.nih.gov/snp
[17]: https://www.ncbi.nlm.nih.gov/clinvar/
[18]: https://www.omim.org/
[19]: http://genetics.bwh.harvard.edu/pph2/
[20]: http://sift.jcvi.org/
[21]: http://fathmm.biocompute.org.uk/
[22]: http://www.internationalgenome.org/
