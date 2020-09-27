# genomic-analysis-test
This repository contains instructions for a genomic analysis test. Please read them entirely before starting.

## Context
2 patients, `Juliette` and `Sacha` were diagnosed with a Chronic Myeloid Leukemia (CML).

In addition to the standard cytogenetic and RT-PCR tests, Bone marrow samples obtained at diagnosis were used to prepare DNA from blastic cells, and this DNA was further enriched for sequences corresponding to 2 regions of chromosome 9 and chromosome 22, respectively, using Agilent capture probes.

Captured DNA was then subjected to illumina paired-end sequencing.

## input datasets
They are available following these links:

[Juliette_R1.fastq.gz](https://lbcd41.snv.jussieu.fr/nextcloud/index.php/s/F8GsBC53pK3pHnQ/download) | md5checksum 8da4b464897e3d528968300e55430760 | 230 Mb

[Juliette_R2.fastq.gz](https://lbcd41.snv.jussieu.fr/nextcloud/index.php/s/EFfJ5pfHJYDCHBi/download) | md5checksum ba6c1610764607d99906d51c1bd682e0 | 285 Mb
 
[Sacha_R1.fastq.gz](https://lbcd41.snv.jussieu.fr/nextcloud/index.php/s/EdtJTQZsaJPTnJ8/download) | md5checksum 694de5808f7046b57734253845a05b08 | 124 Mb

[Sacha_R2.fastq.gz](https://lbcd41.snv.jussieu.fr/nextcloud/index.php/s/bJCb27syGtnqbbJ/download) | md5checksum 631902f941fc7c0b3b8635a87c21758e | 140 Mb

In addition, analysis should be performed using the human reference genome GRCh38/hg38

## Expected Analyses

1. For both patients `Juliette` and `Sacha`, map the sequencing reads, find the covered genomic regions and the corresponding genes.
2. Using the method of your choice, find the **_large_** structural variations that affect both patient genomes and report these findings in vcf files and by any mean you will judge appropriate for discussion with clinician. Please do not focuse on single nucleotide variations or small indels.
3. Comment on the implication of your findings : Diagnosis and Therapie.
4. If the specific protocol used to analyse Juliette and Sacha genomic data was planned to be extended to other patients diagnosed for the same disease, what would be your comments with regards to feasibility, accuracy and sensibility of the test.

## Reporting

FAIRness (Findable, Accessible, Reproducible, Reusable) of analyses are major criteria of their quality.

Beyond your interpretations and conclusions, it is expected that any piece of your analysis is properly reported so that it can be repeated by a third party, to evaluate the strenght of interpretations and conclusions.

Your report has to be addressed to artbio@listes.upmc.fr, this is the only mandatory instruction.
You are free to use any method of your choice to format this report (standalone document, archive, html link, web link, git repository, etc). However, be aware that the quality (FAIRness) of your reporting will be evaluated as a part of the test.

## Time limit

You have a maximum amount of 4 working days (beginning at the time when the test invitation was sent by email) to send your report by any available methode. Whereas no reporting will we taken into account beyond this limit, any partial report available before this limit will of course be considered.

## Support

Computational infrastructure and tools useful for the requested analysis may be found at http://mississippi.sorbonne-universite.fr. Feel free to open a personal account in the Mississippi[2] server.

## Questions

Any question should be raised exclusively using the [`Issues`](https://github.com/ARTbio/genomic-analysis-test/issues) fonctionnality of this respository GitHub. 
For the sake of equality, no answer to questions regarding this test will be made by individual e-mailing.
