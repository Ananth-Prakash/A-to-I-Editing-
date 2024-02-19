Project: Find Mass Spectrometry (MS) evidences for Adenosine to Inosine (AtoI) changes

R script to generate peptide target fasta database, which incorporates AtoI substitutions for Mass Spectrometry data analysis.

To run
Edit file: A_to_I mapping (line 18: max_allowed_edit_sites_per_peptide <- 1)
to specify how many AtoI edit sites are allowed in a peptide fragment

Usage: R CMD BATCH A_to_I_mapping_1mods_perpeptide_updated.R
