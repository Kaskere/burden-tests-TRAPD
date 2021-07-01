# burden-tests-TRAPD
Runs burden test against publicly available genomes. No internal controls needed

Debugged make_snp.py of original repo https://github.com/mhguo1/TRAPD

vcf type - VEP annotated, normalised and with AC, AN tags added

Normalisation - with BCFTools

AC, AN etc. tags can be added by BCFTools plugin
https://samtools.github.io/bcftools/howtos/plugin.fill-tags.html

External controls - gnomAD v3.1 genomes or any other suitable repo

