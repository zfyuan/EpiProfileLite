# EpiProfileLite
One minute analysis of histone post-translational modifications by direct infusion mass spectrometry

In direct infusion MS (DI-MS), histone peptides are collected in several MS scans, and isobaric peptides are collected in specific MS/MS scans (shown in histone_scans_peptides.pdf). EpiProfileLite reads the intensities from MS scans to calculate the percentage of all peptides with the same aa sequence. The unique fragment ions in MS/MS scans are extracted to discriminate isobaric peptide intensities from MS scans.

Four versions are provided: EpiProfileLite_NoNterm means propionylation on unmodified lysine but no propionylation on peptide N-terminus, EpiProfileLite_Nterm means both propionylation on unmodified lysine and peptide N-terminus, and other two mean no QC peptides.
