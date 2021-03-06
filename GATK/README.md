# GATK

The GATK (Genome Analysis Toolkit) is the industry standard for identifying SNPs and indels in germline DNA and RNAseq data. Its scope is now expanding to include somatic variant calling tools, and to tackle copy number (CNV) and structural variation (SV).

![GATK Overview](https://github.com/lynnlangit/TeamTeri/blob/master/Images/GATK-1.png)

They are a commercial company, part of the Broad Institute (https://software.broadinstitute.org/gatk/).

-------

Run GATK with GCP Genomics (https://cloud.google.com/genomics/v1alpha2/gatk). 

Run Picard/GATK tools on GCP cloud-resident genomic data (http://googlegenomics.readthedocs.io/en/latest/use_cases/run_picard_and_gatk/index.html).

NOTE: Picard/GATK tools are command line utilities for genomic sequencing data processing that typically take BAM and other files as input and produce modified BAM files and can be downloaded from this link (http://broadinstitute.github.io/picard/)

These tools are frequently chained together into pipelines to perform step-by-step processing of the sequencing data all the way from unaligned sequencer output to variant calls. For more information see Broad best practices (https://software.broadinstitute.org/gatk/best-practices/).

-------
Alternatively, these tools are available via GCP and the Broad Institute's 'FireCloud'(https://software.broadinstitute.org/firecloud/).  Shown below is a sample screenshot.

![GATK Process on FireCloud, running on GCP](https://github.com/lynnlangit/TeamTeri/blob/master/Images/GATK-FireCloud.png).

-------

Here is more about the GATK process
![GATK Process](https://github.com/lynnlangit/TeamTeri/blob/master/Images/GATK-deep.png).

