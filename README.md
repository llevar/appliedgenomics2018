# JHU EN.601.749: Computational Genomics: Applied Comparative Genomics
Prof: [Michael Schatz](http://schatz-lab.org) (mschatz @ cs.jhu.edu) <br>
TA: [Charlotte Darby](https://github.com/cdarby) (cdarby @ jhu.edu) <br>
Class Hours: Tuesday + Thursday @ 1:30p - 2:45p in Shaffer 304 <br>
Schatz Office Hours: Tuesday + Thursday @ 3-4p in Malone 323 and by appointment <br>
Darby Office Hours: Wednesday @ 4pm in Malone 216 and by appointment <br>

**The primary goal of the course is for students to be grounded in theory and leave the course empowered to conduct independent genomic analyses.** 
We will study the leading computational and quantitative approaches for comparing and analyzing genomes starting from raw sequencing data. The course will focus on human genomics and human medical applications, but the techniques will be broadly applicable across the tree of life. The topics will include genome assembly & comparative genomics, variant identification & analysis, gene expression & regulation, personal genome analysis, and cancer genomics. The grading will be based on assignments, a midterm exam, class presentations, and a significant class project. There are no formal course prerequisites, although the course will require familiarity with UNIX scripting and/or programming to complete the assignments and course project. 

### Prerequisites
- Online introduction to Unix/Linux. Students are strongly recommended to complete one of the following online tutorials (or both) before class begins. 
  - [Code academy's Intro to Unix](https://www.codecademy.com/en/courses/learn-the-command-line/lessons/environment/exercises/bash-profile)
  - [Command line bootcamp](http://rik.smith-unna.com/command_line_bootcamp/?id=9xnbkx6eaof)
  - [Rosalind Bioinformatics Programming in Python](http://rosalind.info/problems/locations/)
  - [Minimal Make](http://kbroman.org/minimal_make/)
- Access to a Linux Machine, and/or Install [VirtualBox](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/virtualbox.md) (Unfortuantely, even Mac will not work correctly for some programs)

## Course Resources:
- [Spring 2017 Course Materials](https://github.com/schatzlab/appliedgenomics2017)
- [Syllabus and Policies](https://github.com/schatzlab/appliedgenomics2018/tree/master/policies)
- [Piazza Discussion Board](https://piazza.com/jhu/spring2018/en601749/home)
- [Journal Club](https://github.com/cdarby/genomicsjc)


## Related Courses & Readings
- [Applied Comparative Genomics by Aaron Quinlan](https://github.com/quinlan-lab/applied-computational-genomics)
- [Algorithms for DNA Sequencing by Ben Langmead](http://www.langmead-lab.org/teaching-materials/)
- [Computational Biology by Rob Patro](https://rob-p.github.io/CSE549F16/lectures/)
- [HarvardX Biomedical Data Science](http://genomicsclass.github.io/book/)
- [PLOS Computational Biology Translational Bioinformatics](http://collections.plos.org/translational-bioinformatics)
- [Biostars Handbook](https://www.biostarhandbook.com/)

## Related Textbooks
- [Molecular Biology of the Gene (Watson et al)](https://www.amazon.com/Molecular-Biology-Gene-James-Watson/dp/0321762436/ref=pd_lpo_sbs_14_t_0?_encoding=UTF8&psc=1&refRID=R6A5BW06E5RJB7GVSNPY)
- [Molecular Biology of the Cell (Alberts)](http://osp.mans.edu.eg/tmahdy/surgeons/ebooks/Books/Alberts%20-%20Molecular%20Biology%20of%20the%20Cell.pdf)
- [Biological Sequence Analysis (Durbin et al)](https://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713)


## Schedule
| # | Date | Lecture | Readings & Resources | Assignment |
|:--|:-----|:--------|:---------------------|:-----------|
|1. | Tu 1/30 | [Introduction](http://schatz-lab.org/appliedgenomics2018/lectures/01.Introduction.pdf) | * [Biological data sciences in genome research (Schatz, 2015, Genome Research)](http://genome.cshlp.org/content/25/10/1417.full) <br> * [Big Data: Astronomical or Genomical? (Stephens et al, 2015, PLOS Biology)](http://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002195) | [Sign Up for Piazza](https://piazza.com/jhu/spring2018/en601749/home) |
|2. | Th 2/1  | [Genomic Technologies](http://schatz-lab.org/appliedgenomics2018/lectures/02.GenomicTechnologies.pdf) | * [Molecular Structure of Nucleic Acid (Watson and Crick, 1953, Nature)](http://www.nature.com/nature/dna50/watsoncrick.pdf) <br> * [Coming of age: ten years of next-generation sequencing technologies (Goodwin et al, 2016, Nature Reviews Genetics)](http://www.nature.com/nrg/journal/v17/n6/full/nrg.2016.49.html) <br> * [High‐throughput sequencing for biology and medicine (Soon et al, 2013, Molecular Systems Biology)](http://msb.embopress.org/content/9/1/640)| [Assignment 1](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/assignment1/README.md)
|3. | Tu 2/6  | [Whole Genome Assembly]()  | * [Velvet: Algorithms for de novo short read assembly using de Bruijn graphs (Zerbino and Birney, 2008, Genome Research)](http://genome.cshlp.org/content/18/5/821.full) <br> * [Quake: quality-aware detection and correction of sequencing errors (Kelley et al, 2010, Genome Biology)](http://genomebiology.biomedcentral.com/articles/10.1186/gb-2010-11-11-r116) <br> * [Allpaths-LG: High-quality draft assemblies of mammalian genomes from massively parallel sequence data (Gnerre et al, 2011, PNAS)](http://www.pnas.org/content/108/4/1513) <br> * [FALCON-unzip: Phased diploid genome assembly with single-molecule real-time sequencing (Chin et al, 2016, Nature Methods)](http://www.nature.com/nmeth/journal/v13/n12/full/nmeth.4035.html) <br>  | 
|4. | Th 2/8  | [Whole Genome Assembly and Alignment]() | * [Toward simplifying and accurately formulating fragment assembly. (Myers, 1995, J. Comp. Bio.)](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.52.6330&rep=rep1&type=pdf) <br> * [MHAP: Assembling large genomes with single-molecule sequencing and locality-sensitive hashing (Berlin et al, 2015, Nature Biotech)](http://www.nature.com/nbt/journal/v33/n6/abs/nbt.3238.html) <br> * [Genome assembly forensics: finding the elusive mis-assembly (Phillippy et al, 2008, Genome Biology)](http://genomebiology.biomedcentral.com/articles/10.1186/gb-2008-9-3-r55) <br> * [MUMmer: Alignment of Whole Genomes (Delcher et al, 1999, NAR)](http://mummer.sourceforge.net/MUMmer.pdf) | [Assignment 2](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/assignment2/README.md)
|5. | Tu 2/13 | [Phylogenetics]() | * [Molecular phylogenetics: principles and practice (Yang and Rannala, 2012, Nature Reviews Genetics)](https://www.nature.com/articles/nrg3186) |
|6. | Th 2/15 | [Read Mapping]() | * [How to map billions of short reads onto genomes (Trapnell and Salzberg, 2009, Nature Biotech)](http://www.nature.com/nbt/journal/v27/n5/full/nbt0509-455.html) <br> * [Bowtie: Ultrafast and memory-efficient alignment of short DNA sequences to the human genome (Langmead et al, 2009, Genome Biology)](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2009-10-3-r25) <br> * [BWA-MEM: Aligning sequence reads, clone sequences and assembly contigs with BWA-MEM (Li, 2013, arXiv)](https://arxiv.org/abs/1303.3997) <br> * [SAM/BAM/Samtools: The Sequence Alignment/Map format and SAMtools (Li et al, 2009, Bioinformatics)](https://academic.oup.com/bioinformatics/article/25/16/2078/204688/The-Sequence-Alignment-Map-format-and-SAMtools) <br> * [IGV: Integrative genomics viewer (Robinson et al, 2011, Nature Biotech)](http://www.nature.com/nbt/journal/v29/n1/full/nbt.1754.html) | [Assignment 3](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/assignment3/README.md)
|7. | Tu 2/20 | [Variant Analysis]() | * [PolyBayes: A general approach to single-nucleotide polymorphism discovery (Marth et al, 1999, Nature Genetics)](http://www.nature.com/ng/journal/v23/n4/full/ng1299_452.html) <br> * [GATK: A framework for variation discovery and genotyping using next-generation DNA sequencing data (Depristo et al, 2011, Nature Genetics)](http://www.nature.com/ng/journal/v43/n5/full/ng.806.html) <br> * [Scalpel: Accurate de novo and transmitted indel detection in exome-capture data using microassembly (Narzisi et al, 2014, Nature Methods)](http://www.nature.com/nmeth/journal/v11/n10/full/nmeth.3069.html) | 
|8. | Th 2/22 | [Structural Variant Analysis]() | * [Genome structural variation discovery and genotyping (Alkan et al, 2011, Nature Reviews Genetics)](http://www.nature.com/nrg/journal/v12/n5/full/nrg2958.html) <br> * [LUMPY: a probabilistic framework for structural variant discovery (Layer et al, 2014, Genome Biology)](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-6-r84) <br> * [Assembly Reconciliation (Zimin et al, 2008, Bioinformatics)](https://academic.oup.com/bioinformatics/article/24/1/42/205726/Assembly-reconciliation) <br> * [Resolving the complexity of the human genome using single-molecule sequencing (Chaisson et al, 2015, Nature)](http://www.nature.com/nature/journal/v517/n7536/abs/nature13907.html)  | [Assignment 4](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/assignment4/README.md)
|9. | Tu 2/27 | [Genome Arithmetic]() | * [BEDTools: a flexible suite of utilities for comparing genomic features (Quinlan & Hall, 2010, Bioinformatics)](https://academic.oup.com/bioinformatics/article/26/6/841/244688/BEDTools-a-flexible-suite-of-utilities-for) <br> * [A Parallel Algorithm for N-Way Interval Set Intersection (Layer & Quinlan, 2016, IEEE Proceedings)](http://ieeexplore.ieee.org/document/7289350/?tp=&arnumber=7289350&url=http:%2F%2Fieeexplore.ieee.org%2Fiel7%2F5%2F4357935%2F07289350.pdf%3Farnumber%3D7289350) |
|10. | Th 3/1  | [Genome Annotation]() | * [BLAST: Basic Local Alignment Search Tool](http://s3.amazonaws.com/academia.edu.documents/25023760/altschul1990.pdf?AWSAccessKeyId=AKIAIWOWYYGZ2Y53UL3A&Expires=1488914265&Signature=zX6z9PyBMXesvcCdR3PTHVO%2BtFU%3D&response-content-disposition=inline%3B%20filename%3DBasic_local_alignment_search_tool.pdf) <br> * [Glimmer: Microbial gene identification using interpolated Markov models](http://www.cs.jhu.edu/~genomics/Glimmer/glimmer-nar.pdf) <br> * [MAKER2: an annotation pipeline and genome-database management tool for second-generation genome projects](http://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-12-491) <br> * [What is a hidden Markov model?](http://www.nature.com/nbt/journal/v22/n10/full/nbt1004-1315.html)  | [Assignment 5](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/assignment5/README.md)
|11. | Tu 3/6  | [Functional Analysis 1: RNA-seq]() | * [RNA-Seq: a revolutionary tool for transcriptomics (Wang et al, 2009. Nature Reviews Genetics)](http://www.nature.com/nrg/journal/v10/n1/full/nrg2484.html)<br> * [Differential gene and transcript expression analysis of RNA-seq experiments with TopHat and Cufflinks (Trapnell et al, 2012, Nature Protocols)](http://www.nature.com/nprot/journal/v7/n3/full/nprot.2012.016.html)<br> * [Salmon provides fast and bias-aware quantification of transcript expression (Patro et al, 2017, Nature Methods)](http://www.nature.com/nmeth/journal/vaop/ncurrent/full/nmeth.4197.html)<br> * [Bismark: a flexible aligner and methylation caller for Bisulfite-Seq applications (Krueger and Andrews, 2011, Bioinformatics)](https://academic.oup.com/bioinformatics/article/27/11/1571/216956/Bismark-a-flexible-aligner-and-methylation-caller) | 
|12. | Th 3/8  | [Functional Analysis 2: Methyl-seq & Chip-seq]() | * [ChIP–seq and beyond: new and improved methodologies to detect and characterize protein–DNA interactions (Furey, 2012, Nature Reviews Genetics)](http://www.nature.com/nrg/journal/v13/n12/abs/nrg3306.html)<br> * [PeakSeq enables systematic scoring of ChIP-seq experiments relative to controls (Rozowsky et al. 2009. Nature Biotech)](http://www.nature.com/nbt/journal/v27/n1/full/nbt.1518.html) | [Project Proposal](https://github.com/schatzlab/appliedgenomics/blob/master/assignments/projects/projectproposal.md) 
|13. | Tu 3/13 | [Functional Analysis 3: Regulatory States]() | * [ChromHMM: automating chromatin-state discovery and characterization (Ernst & Kellis, 2012, Nature Methods)](http://www.nature.com/nmeth/journal/v9/n3/full/nmeth.1906.html) <br> * [Segway: Unsupervised pattern discovery in human chromatin structure through genomic segmentation (Hoffman et al, 2012, Nature Methods)](http://www.nature.com/nmeth/journal/v9/n5/full/nmeth.1937.html) |
|14. | Th 3/15 | [Functional Analysis 4: ENCODE]() | * [An integrated encyclopedia of DNA elements in the human genome (The ENCODE Project Consortium, Nature, 2012)](http://www.nature.com/nature/journal/v489/n7414/full/nature11247.html) | [Assignment 6](https://github.com/schatzlab/appliedgenomics2018/blob/master/assignments/assignment6/README.md)
| | Tu 3/20 | *Spring Break!*
| | Th 3/22 | *Spring Break!*
|15. | Tu 3/27 | [Functional Analysis 5: Single Cell Genomics]() | * [Ginkgo: Interactive analysis and assessment of single-cell copy-number variations (Garvin et al, 2015, Nature Methods)](http://www.nature.com/nmeth/journal/v12/n11/full/nmeth.3578.html) <br> 
|16. | Th 3/29 | [Midterm Review]()
|17. | Tu 4/3  | Midterm Exam | | In class Midterm
|18. | Th 4/5  | [Midterm Discussion]()
|19. | Tu 4/10 | [Human Evolution]() | * [An integrated map of genetic variation from 1,092 human genomes (1000 Genomes Consortium, 2012, Nature)](http://www.nature.com/nature/journal/v491/n7422/full/nature11632.html) <br> * [Analysis of protein-coding genetic variation in 60,706 humans (Let et al, 2016, Nature)](http://www.nature.com/nature/journal/v536/n7616/full/nature19057.html) <br> * [A Draft Sequence of the Neandertal Genome (Green et al. 2010, Science)](http://science.sciencemag.org/content/328/5979/710.full) <br> * [Excavating Neandertal and Denisovan DNA from the genomes of Melanesian individuals (Vernot et al. 2016. Science)](http://science.sciencemag.org/content/early/2016/03/16/science.aad9416.full) <br> * [Visualizing Data Using t-SNE](https://www.youtube.com/watch?v=RJVL80Gg3lA) |
|20. | Th 4/12 | [Human Genetic Diseases]() | * [Genome-Wide Association Studies (Bush & Moore, 2012, PLOS Comp Bio)](https://doi.org/10.1371/journal.pcbi.1002822) <br> * [The contribution of de novo coding mutations to autism spectrum disorder (Iossifov et al, 2014, Nature)](https://www.nature.com/nature/journal/v515/n7526/full/nature13908.html)
|21. | Tu 4/17 | [Cancer Genomics]() | * [The Hallmarks of Cancer (Hanahan & Weinberg, 2000, Cell)](http://www.sciencedirect.com/science/article/pii/S0092867400816839) <br> * [Evolution of Cancer Genomes (Yates & Campbell, 2012, Nature Reviews Genetics)](http://www.nature.com/nrg/journal/v13/n11/full/nrg3317.html) <br> * [Comprehensive molecular portraits of human breast tumours (TCGA, 2012, Nature)](http://www.nature.com/nature/journal/v490/n7418/full/nature11412.html) | [Preliminary Project Report](https://github.com/schatzlab/appliedgenomics/blob/master/assignments/projects/preliminaryreport.md)
|22. | Th 4/19 | [Microbiome and Metagenomics]() | * [Kraken: ultrafast metagenomic sequence classification using exact alignments (Wood and Salzberg, 2014, Genome Biology)](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2014-15-3-r46) <br> * [Chapter 12: Human Microbiome Analysis (Morgan and Huttenhower)](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1002808)
|23. | Tu 4/24 |[Genomic Futures]() | * ["Snyderome" Personal Omics Profiling Reveals Dynamic Molecular and Medical Phenotypes (Chen et al, 2012, Cell)](http://www.sciencedirect.com/science/article/pii/S0092867412001663) <br> * [Identifying Personal Genomes by Surname Inference (Gymrek et al, 2013, Science)](http://science.sciencemag.org/content/339/6117/321) | [Project Presentations]() 
|24. | Th 4/26| [Project Presentations]() | | [Project Presentations]()
|25. | Tu 5/1  | [Project Presentations]() | | [Project Presentations]()
|26. | Th 5/3  | [Project Presentations]() | | [Project Presentations]()
|27. | Wed 5/16 | Final Project Report Due! | | [Final Project Report]()

