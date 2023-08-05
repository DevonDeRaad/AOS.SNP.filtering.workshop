SNP filtering workshop - AOS - August 8th, 2023
----------------------------------------------------

Welcome to the 2023 AOS SNP filtering workshop! During our half day together, we will be going over the details of SNP filtering. Topics will include:
*   Background on the details of next-gen (i.e., Illumina) sequencing.
*   Overview of the general process of converting raw Illumina reads (.fastq.gz files) into a set of polymorphic sites shared among your samples (called SNPs) stored in a variant call format (vcf) file.
*   Review of the possible biases introduced by DNA sequencing, read alignment, and SNP calling.
*   Specific filters that we can implement to ameliorate these biases.
*   Advice on the ideal order for implementing specific filters in your SNP filtering pipeline.
*   Hands on experience filtering a SNP dataset.
*   Preliminary population genetic analyses.
  
----------------------------------------------------

### Required materials:
*  A personal laptop.

### Materials highly encouraged to bring to the workshop:
*  A working RStudio installation
*  Working installations of the R packages 'SNPfiltR' and 'vcfR'
*  An unfiltered SNP dataset that you are interested in analyzing

If you have an unfiltered SNP dataset that you would like to work on filtering, that is great, as the nuances of each dataset will require unique parameter settings, and this is a great time to work through that process.
If you don't currently have your own SNP dataset that is ready for filtering, that is no problem, and I encourage you to download the one publicly available here: <https://github.com/DevonDeRaad/aph.rad/blob/master/populations.snps.vcf.gz>.

During the working session, we will be working through the following SNP filtering tutorial: <https://devonderaad.github.io/SNPfiltR/articles/scrub-jay-RADseq-vignette.html>

If you finish the filtering tutorial early, I highly encourage you to try using your brand-new filtered SNP dataset as input for some interesting evolutionary analyses detailed in the tutorials found here: <https://github.com/DevonDeRaad/Fall.2022.RAD.workshop/tree/main/week11>

----------------------------------------------------

### Proposed structure
*  1:00-1:15PM Group introductions.
*  1:15-1:45PM Introductory lecture.
*  1:45-2:15PM Participants work on the pre-designed SNP filtering tutorial.
*  2:15-2:30PM Break for coffee & snacks.
*  2:30-4:00PM 90-minute bio-informatics working session for participants to continue following the SNP filtering tutorial.
