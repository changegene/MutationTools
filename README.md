# MutationTools
Collected methods of mutation detection from WGS/WES

## SNV/INDEL/SV
- [SpeedSeq](https://github.com/hall-lab/speedseq)

## Capture-Seq
- [BAMClipper](https://github.com/tommyau/bamclipper) -- Remove primer sequence from BAM alignments by soft-clipping


## telomerecat
- [Telomerecat](https://telomerecat.readthedocs.io/en/latest/) docker pull jhrf/telomerecat

## Estimation of Temporal Ordering of Cancer Abnormalities
- [GRAFT](https://www.sanger.ac.uk/science/tools/graft) (Genomic Rearrangement Assembly For Tumours) is an algorithm designed to time rearrangements.
- [cancerTiming](https://cran.r-project.org/web/packages/cancerTiming/index.html)
- [ReMixT](https://bitbucket.org/dranew/remixt)
- [THEMIS](https://github.com/jieliu6/THEMIS)
- [TRONCO](https://sites.google.com/site/troncopackage/home)

- [PyClone](https://github.com/aroth85/pyclone)
 基于SNV/indel CCF 
 基于CNV CCF 
 
- [sciclone]
 基于SNV/indel VAF

## virus integration
- [VirTect](https://github.com/WGLab/VirTect)


## SV
- [GRIDSS](https://github.com/PapenfussLab/gridss)


## Mutation software
- [scalpel](http://scalpel.sourceforge.net/manual.html): Find (somatic or de novo) indel from WGS/WES 
- [MuSiC2](https://github.com/ding-lab/MuSiC2):Identifying mutational significance in cancer genomes
- [SomaticSeq](http://bioinform.github.io/somaticseq/): An ensemble approach to accurately detect somatic mutations

## signature
- [Mutational Signatures](http://cancer.sanger.ac.uk/cosmic/signatures) From COSMIC
- [mSignatureDB](http://tardis.cgu.edu.tw/msignaturedb/)
- [SigProfiler](http://cn.mathworks.com/matlabcentral/fileexchange/38724-sigprofiler?requestedDomain=true)
- [EMu](https://github.com/andrej-fischer/EMu)
- [SomaticSignatures](https://bioconductor.org/packages/release/bioc/html/SomaticSignatures.html)
- [mutation-signatures](https://github.com/mskcc/mutation-signatures)
- [MutationalPatterns](https://github.com/UMCUGenetics/MutationalPatterns)

## Germline mutation
- [germVar2](https://github.com/rj67/germVar2)

## Mutation & pathway enrichment
###
- [MuSiC](http://gmt.genome.wustl.edu/packages/genome-music/index.html)
[Example](http://wp.zxzyl.com/?p=276)

## Driver mutation from Cancer sequencing data set of multiple samples ()
1. [MuSiC-SMG/MutSigCV](http://software.broadinstitute.org/cancer/software/genepattern/modules/docs/MutSigCV) 
- [Docker-MutSigCV](https://hub.docker.com/r/argrosso/mutsigcv/)

Identify genes mutated more frequently than background mutation rate based on patient-based factors and genomic position-based factors.
 - The patient-based factors include:
overall mutation rate
overall mutational spectrum (e.g., the percentages of mutations that are transitions of certain types, transversions of certain types, and/or nonsense)
 - The genomic position-based factors include:
gene expression levels.
DNA replication timing.
HiC-based chromatin state estimation.

2. [OncodriveCLUST](https://bitbucket.org/bbglab/oncodriveclust) Gain-of-function--Oncogene

OncodriveCLUST is a method aimed to identify genes whose mutations are biased towards a large spatial clustering. This method is designed to exploit the feature that mutations in cancer genes, especially oncogenes, often cluster in particular positions of the protein.

Database used for OncodriveCLUST
- [CGC](http://cancer.sanger.ac.uk/census/) Belong to COSMIC
  need regist
- [DriverDBv2](http://driverdb.tms.cmu.edu.tw/driverdbv2/)
Integrated several database and annotated with several prediction software

3. [OncodriveFM](https://bitbucket.org/bbglab/oncodrivefm) Lose-of-function--Tumor superessor gene

OncodriveFM detects candidate cancer driver genes and pathways from catalogs of somatic mutations in a cohort of tumors by computing the bias towards the accumulation of functional mutations (FM bias).

4. [ActiveDriver](https://cran.r-project.org/web/packages/ActiveDriver/index.html)

A mutation analysis tool that discovers cancer driver genes with frequent mutations in protein signalling sites such as post-translational modifications (phosphorylation, ubiquitination, etc)

5. [Dendrix]
6. [MDPFinder]
7. [Simon]
8. [NetBox]
9. [CoMPD]
10. [DawnRank]
11. [DriverNet]
12. [e-Driver]
13. [iPAC]
14. [MSEA]

## non-coding driver mutation
- [LARVA](http://larva.gersteinlab.org/)
- [OncodriveFML](http://bbglab.irbbarcelona.org/oncodrivefml/home)



### Transposable element detection
- [TEPID](https://github.com/ListerLab/TEPID)
- [Mobster](https://sourceforge.net/projects/mobster/)

## Knowledge
- [SVs](http://biosb.nl/wp-content/uploads/2014/10/Day-2-Guryev-CNV-calling-in-Gene-Panels.pdf)
