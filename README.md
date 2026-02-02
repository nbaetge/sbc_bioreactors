# sbc_bioreactors

This repository contains data and analysis from work conducted as a part of an NSF OCE-PRF project (Award number 2306993) and the Simons Foundation International’s BIOS-SCOPE3 program, being prepared for manuscript submission to a journal for peer-review. The goal of this work was to assess the use of marine bioreactors to estimate dissolved organic matter bioavailability. 

All code and data provided in this repository are freely available for use. Please do not hesitate to contact me if you have questions or comments or if you find errors/inaccuracies.

The analyses can be replicated as follows:

-Clone repository

-Open R project

-Run scripts in this order:

1_sbc_bioreactors_conditioning.Rmd
2_sbc_bioreactors_serial_configuration.Rmd
3_sbc_bioreactors_bottle_comparison.Rmd
4_sbc_bioreactors_DADA2.Rmd
5_sbc_bioreactors_phyloseq.Rmd
S1_sbc_bioreactors_o2_tracer.s.Rmd
S2_sbc_bioreactors_bottle_ba_and_doc.Rmd
S3_sbc_bioreactors_nitrogen.Rmd

*Please be aware that you will need to change path names where appropriate. 
**Please also note that Fastq files have not been uploaded, but DADA2 output are available here. The SILVA reference library used in the analysis (SILVA_SSU_r138_2_2024) has also not been uploaded. 